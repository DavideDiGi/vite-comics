<script>
import AppCards from './AppCards.vue';

export default {
    name: 'AppMain',
    components: {
        AppCards
    },

}
</script>

<template>

    <main>

        <div class="container">
            <AppCards />
        </div>

    </main>

</template>

<style lang="scss" scoped>
main {
    width: 100vw;
    background-color: black;
    padding: 50px 0;

    .container {
        width: 80vw;
        margin: 0 auto;
        color: white;
    }

}
</style>