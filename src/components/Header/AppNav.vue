<script>

export default {
    name: 'AppNav'
}

</script>

<template>

    <nav>

        <ul>

            <li><a href="#">CHARACTERS</a></li>
            <li><a class="active" href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>

        </ul>

    </nav>

</template>

<style lang="scss" scoped>
nav {
    height: 100%;

    ul {
        list-style: none;
        display: flex;
        height: 100%;

        li {

            padding: 0 15px;
            height: 100%;

            a {
                color: black;
                text-decoration: none;
                font-size: 0.8rem;
                height: 100%;

                &.active {
                    color: rgb(56, 128, 241);
                    border-bottom: 5px solid rgb(56, 128, 241);
                    display: inline-block;
                }

            }

        }
    }
}
</style>