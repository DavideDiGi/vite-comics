<script>
import AppTop from '../Footer/AppTop.vue';
import AppMiddle from '../Footer/AppMiddle.vue';
import AppBottom from '../Footer/AppBottom.vue';

export default {
    name: "AppFooter",
    components: {
        AppTop,
        AppMiddle,
        AppBottom
    }
}
</script>

<template>

    <footer>

        <div>

            <AppTop />
            <AppMiddle />
            <AppBottom />

        </div>

    </footer>

</template>

<style lang="scss" scoped>

</style>