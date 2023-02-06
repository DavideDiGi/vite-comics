<script>
import AppCards from './AppCards.vue';
import AppJumbotron from './AppJumbotron.vue';

export default {
    name: 'AppMain',
    components: {
        AppCards,
        AppJumbotron
    }
}
</script>

<template>

    <main>
        <AppJumbotron />
        <div class="container">
            <AppCards />
        </div>

    </main>

</template>

<style lang="scss">
main {
    width: 100vw;
    background-color: black;

    .container {
        width: 80vw;
        margin: 0 auto;
        color: white;
    }

}
</style>