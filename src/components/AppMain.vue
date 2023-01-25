<script>
export default {
    name: 'AppMain',
}
</script>

<template>

    <main>
        <div class="container main-content">
            <h2> Content 1 </h2>
            <h2> Content 2 </h2>
        </div>
    </main>

</template>

<style lang="scss" scoped>
main {
    background-color: black;
}

.main-content {
    min-height: 150px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

h2 {
    margin-top: 1rem;
    margin-bottom: 1rem;
    color: white;
}
</style>