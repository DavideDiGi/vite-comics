<script>

export default {
    name: 'AppTop'
}

</script>

<template>

    <div class="topFooter">
        <div class="container">
            <ul>

                <li>
                    <a href="#">

                        <img src="../../assets/img/buy-comics-digital-comics.png" alt="">

                        <span>
                            DIGITAL COMICS
                        </span>

                    </a>
                </li>

                <li>
                    <a href="#">

                        <img src="../../assets/img/buy-comics-merchandise.png" alt="">

                        <span>
                            DC MERCHANDISE
                        </span>

                    </a>
                </li>

                <li>
                    <a href="#">

                        <img src="../../assets/img/buy-comics-subscriptions.png" alt="">

                        <span>
                            SUBSCRIPTION
                        </span>

                    </a>
                </li>

                <li>
                    <a href="#">

                        <img src="../../assets/img/buy-comics-shop-locator.png" alt="">

                        <span>
                            COMIC SHOP LOCATOR
                        </span>

                    </a>
                </li>

                <li>
                    <a href="#">

                        <img src="../../assets/img/buy-dc-power-visa.svg" alt="">

                        <span>
                            DC POWER VISA
                        </span>

                    </a>
                </li>


            </ul>
        </div>
    </div>


</template>

<style lang="scss" scoped>
.topFooter {
    width: 100vw;
    background-color: rgb(56, 128, 241);
    padding: 50px 0;

    .container {
        width: 80vw;
        margin: 0 auto;

        ul {
            list-style: none;
            display: flex;
            justify-content: space-around;

            li {

                a {
                    color: white;
                    text-decoration: none;
                    font-size: 0.8rem;
                    display: flex;
                    align-items: center;
                    justify-content: space-between;

                    img {
                        max-height: 50px;
                        max-width: 50px;
                        margin-right: 15px;
                    }

                }

            }
        }
    }
}
</style>