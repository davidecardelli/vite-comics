<script>
export default {
    name: 'AppHeader',
}
</script>

<template>
    <header>
        <figure>
            <a href="#"><img src="../assets/img/dc-logo.png" alt="DC Comics"></a>
        </figure>
        <nav>
            <ul>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Collectibles</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">Fans</a></li>
                <li><a href="#">News</a></li>
                <li><a href="#">Shop</a></li>
            </ul>
        </nav>
    </header>


</template>

<style scoped>
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