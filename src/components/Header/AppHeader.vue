<script>
import AppLogo from './AppLogo.vue';
import AppNav from './AppNav.vue';

export default {
    name: 'AppHeader',
    components: {
        AppLogo,
        AppNav,

    }
}
</script>

<template>

    <header>

        <div>
            <AppLogo />
        </div>
        <div>
            <AppNav />
        </div>

    </header>

</template>

<style lang="scss" scoped>

</style>