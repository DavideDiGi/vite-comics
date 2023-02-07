<script>

export default {
    name: 'AppCards',
    props: {
        series: String,
        thumb: String
    }
}

</script>

<template>

    <a href="#" class="card">
        <div class="card-cover"> <img :src="thumb" :alt="series"></div>
        <div class="card-title">{{ series }}</div>
    </a>

</template>

<style lang="scss" scoped>
.card {
    width: calc(100% / 6);
    height: 300px;
    padding: 10px;
    border: 1px solid black;
    text-decoration: none;
    color: white;
    display: inline-block;

    .card-cover {
        background-color: gold;
        height: 80%;

        img {
            width: 100%;
            height: 100%;
        }
    }

    .card-title {
        margin-top: 10px;
        font-size: 0.8rem;
    }
}
</style>