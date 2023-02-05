<script>

export default {
    name: 'AppMiddle'
}

</script>

<template>

    <div class="middleFooter">

        <div class="container">

            <div class="links-container">

                <div class="comics">

                    <h3>DC COMICS</h3>

                    <a href="#">Characters</a>
                    <a href="#">Comics</a>
                    <a href="#">Movies</a>
                    <a href="#">TV</a>
                    <a href="#">Games</a>
                    <a href="#">Videos</a>
                    <a href="#">News</a>

                </div>
                <div class="shop">

                    <h3>SHOP</h3>

                    <a href="#">Shop DC</a>
                    <a href="#">Shop DC Collectibles</a>


                </div>
                <div class="dc">

                    <h3>DC</h3>

                    <a href="#">Terms Of Use</a>
                    <a href="#">Privacy Policy (New)</a>
                    <a href="#">Ad choices</a>
                    <a href="#">Advertising</a>
                    <a href="#">Jobs</a>
                    <a href="#">Subscriptions</a>
                    <a href="#">Talent Workshops</a>
                    <a href="#">CPSC Certificates</a>
                    <a href="#">Ratings</a>
                    <a href="#">Shop Help</a>
                    <a href="#">Contact Us</a>

                </div>
                <div class="sites">

                    <h3>SITES</h3>

                    <a href="#">DC</a>
                    <a href="#">MAD Magazine</a>
                    <a href="#">DC Kids</a>
                    <a href="#">DC Universe</a>
                    <a href="#">DC Power Visa</a>

                </div>


            </div>

            <div class="bg-logo-container"></div>

        </div>
    </div>

</template>

<style lang="scss" scoped>
.middleFooter {
    width: 100vw;
    background-image: url(../../assets/img/footer-bg.jpg);
    background-size: 1800px;

    .container {
        width: 80vw;
        margin: 0 auto;
        display: flex;

        .bg-logo-container {
            background-image: url(../../assets/img/dc-logo-bg.png);
            background-repeat: no-repeat;
            width: 65%;
            background-position-x: 180px;
            background-position-y: -80px;
        }

        .links-container {
            max-height: 300px;
            width: 35%;
            display: flex;
            flex-wrap: wrap;
            flex-direction: column;
            margin: 50px 0;


            >div {
                margin-right: 30px;
                color: white;

                h3 {
                    margin-bottom: 10px;
                }

                a {
                    line-height: 1.5rem;
                    font-size: 0.8rem;
                    color: grey;
                    display: block;
                    text-decoration: none;
                }

                &.shop {
                    margin-top: 20px;
                }
            }
        }

    }
}
</style>