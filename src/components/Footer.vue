<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="items">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </div>
                <div class="items">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>dc merchandise</span>
                </div>
                <div class="items">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>subscription</span>
                </div>
                <div class="items">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>comic shop locator</span>
                </div>
                <div class="items">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="" class="little">
                    <span>dc power visa</span>
                </div>
            </div>
        </div>
        <div class="footer-center">
            <div class="container clearfix">
                <div class="first-col">
                    <h3>dc comics</h3>
                    <ul>
                        <li><a>Characters</a></li>
                        <li><a>Comics</a></li>
                        <li><a>Movies</a></li>
                        <li><a>TV</a></li>
                        <li><a>Games</a></li>
                        <li><a>Videos</a></li>
                        <li><a>News</a></li>
                    </ul>
                    <h3>shop</h3>
                    <ul>
                        <li><a>Shop DC</a></li>
                        <li><a>Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="second-col">
                    <h3>dc</h3>
                    <ul>
                        <li><a>Terms Of Use</a></li>
                        <li><a>Privacy policy (New)</a></li>
                        <li><a>Ad Choiches</a></li>
                        <li><a>Advertising</a></li>
                        <li><a>Jobs</a></li>
                        <li><a>Subscriptions</a></li>
                        <li><a>Talent Workshops</a></li>
                        <li><a>CPSC Certificates</a></li>
                        <li><a>Ratings</a></li>
                        <li><a>Shop Help</a></li>
                        <li><a>Contact Us</a></li>
                    </ul>
                </div>
                <div class="third-col">
                    <h3>sites</h3>
                    <ul>
                        <li><a>DC</a></li>
                        <li><a>MAD Magazine</a></li>
                        <li><a>DC Kids</a></li>
                        <li><a>DC Universe</a></li>
                        <li><a>DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="container"></div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    data(){
        return {
            title: "Lorem Ipsum"
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";
    .footer-top {
        background-color: $lightblue;
        .container {
            display: flex;
            justify-content: space-between;
            padding: 0 2em;
            .items {
                padding: 3em 0;
                display: flex;
                align-items: center;
                img {
                    height: 60px;
                    &.little {
                        height: 40px;
                    }
                }
                span {
                    text-transform: uppercase;
                    padding-left: 1em;
                    color: white;
                    font-size: 0.8em;
                }
            }
        }
    }

    .footer-center {
        background-image: url(../assets/img/footer-bg.jpg);
        .clearfix::after {
            content: "";
            clear: both;
            display: table;
        }
        .container {
            padding: 2em 0 2em 0;
            .first-col, .second-col, .third-col {
            float: left;
            width: 15%;
            h3 {
                text-transform: uppercase;
                padding: 0.8em 0;
                color: white;
            }
            ul {
                list-style: none;
                li {
                    padding-bottom: 0.5em;
                    font-size: 0.9em;
                    a {
                        text-decoration: none;
                        color: $footerGreyText;
                    }
                }
            }
        }
        }
        
    }

    .footer-bottom {
        background-color: $footerBottomBackground;
    }
</style>