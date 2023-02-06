<script>

export default {
    name: 'AppJumbotron'
}

</script>

<template>

    <div class="jumbotron">

        <div class="container">
            <button class="big button">CURRENT SERIES</button>
        </div>

    </div>

</template>

<style lang="scss" >
.jumbotron {
    color: white;
    width: 100%;
    height: 300px;
    background-color: red;
    margin-bottom: 40px;
    background-image: url(../../assets/img/jumbotron.jpg);
    background-size: cover;
    position: relative;

}

.button {
    background-color: rgb(56, 128, 241);
    border-style: none;
    color: white;
    font-weight: bold;
    cursor: pointer;

    &.big {
        font-size: 1.5rem;
        position: absolute;
        bottom: -7%;
        padding: 10px 20px;
    }
}
</style>