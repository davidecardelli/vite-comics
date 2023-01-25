<script>
export default {
    name: 'AppCard',
    data() {
        return {
        }
    },
    props: {
        img: String,
        title: String
    }
}

</script>

<template>

    <div class="card">
        <img :src="img" :alt="title">
        <h4>{{ title }}</h4>
    </div>

</template>

<style lang="scss" scoped>
.card {
    flex-basis: calc(100% / 6);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 1rem 0;

    img {
        width: 150px;
        height: 150px;
        text-align: center;
    }

    h4 {
        color: white;
        text-align: center;
        padding-top: 1rem;
    }
}
</style>