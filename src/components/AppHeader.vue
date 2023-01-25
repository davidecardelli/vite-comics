<script>
export default {
    name: 'AppHeader',

    data() {
        return {
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]
        }
    }

}
</script>

<template>
    <header class="container">
        <figure>
            <a href="#"><img src="../assets/img/dc-logo.png" alt="DC Comics"></a>
        </figure>
        <nav>
            <ul>
                <li v-for="link in links"><a :href="link.url">{{ link.text }}</a></li>
            </ul>
        </nav>
    </header>


</template>

<style lang="scss" scoped>
header {
    height: 150px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul {
    display: flex;
    gap: 20px;
}

a {
    color: black;
    text-transform: uppercase;
}
</style>