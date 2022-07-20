<template>
    <header>
        <img src="../assets/dc-logo.png" alt="DC    Logo">
        <nav>
            <ul>
                <li v-for="(element, index) in navList" :key="index">
                    {{ element.text }}
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'MainContent',

    data: function() {
        return {
            navList: [
                {
                text: "characters",
                href: "#"
                },
                {
                text: "comics",
                href: "#"
                },
                {
                text: "movies",
                href: "#"
                },
                {
                text: "tv",
                href: "#"
                },
                {
                text: "games",
                href: "#"
                },
                {

                text: "collectibles",
                href: "#"
                },
                {
                text: "videos", 
                href: "#"
                },
                {
                text: "fans",
                href: "#"
                },
                {
                text: "news",
                href: "#"
                },
                {
                text: "shop",
                href: "#"
                },
                {
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>

header{
    display: flex;
    justify-content: space-evenly;
    margin-top: 1rem;
    margin-bottom: 1rem;
}
li {
    list-style: none;
    display: inline-block;
    font-size: .6rem;
    padding: 1rem;
    text-transform: uppercase;
    cursor: pointer;
    &:hover {
            border-bottom: 5px solid #0282F9;
            color: #0282F9;
        }
}
img{
    height:4rem;
}

</style>