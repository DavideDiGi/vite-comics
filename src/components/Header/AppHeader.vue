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
        <div class="container box-header">

            <div>
                <AppLogo />
            </div>

            <div class="nav-container">
                <AppNav />
            </div>

        </div>
    </header>

</template>

<style lang="scss" scoped>
header {
    width: 100vw;
    height: 100px;

    .container {
        width: 80vw;
        margin: 0 auto;

        &.box-header {
            background-color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-height: 120px;
            height: 100%;

            .nav-container {
                height: 100%;
                line-height: 100px;

            }
        }
    }
}
</style>