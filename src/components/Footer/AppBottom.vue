<script>

export default {
    name: 'AppBottom'
}

</script>

<template>

    <div class="bottomFooter">

        <div class="container">

            <div class="sign-up">
                <a href="#">SIGN-UP NOW!</a>
            </div>

            <div class="socials">

                <span>FOLLOW US</span>

                <div class="socials-links">

                    <a href="#"><span><img src="../../assets/img/footer-facebook.png" alt=""></span></a>
                    <a href="#"><span><img src="../../assets/img/footer-twitter.png" alt=""></span></a>
                    <a href="#"><span><img src="../../assets/img/footer-youtube.png" alt=""></span></a>
                    <a href="#"><span><img src="../../assets/img/footer-pinterest.png" alt=""></span></a>
                    <a href="#"><span><img src="../../assets/img/footer-periscope.png" alt=""></span></a>

                </div>
            </div>

        </div>

    </div>

</template>

<style lang="scss" scoped>
.bottomFooter {
    width: 100vw;
    background-color: rgb(48, 48, 48);
    height: 100px;
    display: flex;
    align-items: center;


    .container {
        width: 80vw;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;

        .sign-up {
            color: white;
            padding: 10px;
            border: 2px solid rgb(56, 128, 241);


            a {
                font-size: 0.9rem;
                font-weight: bold;
                text-decoration: none;
                color: white;
            }
        }

        .socials {
            display: flex;
            align-items: center;

            >span {
                color: rgb(56, 128, 241);
                font-weight: bold;
                margin-right: 20px;
            }

            .socials-links {

                a {
                    text-decoration: none;
                    margin-right: 15px;

                    img {
                        width: 30px;
                    }
                }
            }
        }
    }
}
</style>