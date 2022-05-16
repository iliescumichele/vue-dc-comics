<template>
    <footer>
        <div class="top-foot">
            <div class=" container clearfix">
                <div class="col-sx">
                    <strong>DC COMICS</strong>
                    <ul>
                        <li><a href="">Characers</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>

                    <strong>SHOP</strong>
                    <ul>
                        <li><a href="">Shop DC</a></li>
                        <li><a href="">Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="col-center">
                    <strong>DC</strong>
                    <ul>
                        <li><a href="">Terms of Use</a></li>
                        <li><a href="">Privacy policy</a></li>
                        <li><a href="">Ad choices</a></li>
                        <li><a href="">advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscription</a></li>
                        <li><a href="">Talent Workshop</a></li>
                        <li><a href="">CPSC certification</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop Help</a></li>
                        <li><a href="">Contact Us</a></li>
                    </ul>
                </div>
                <div class="col-dx">
                    <strong>SITES</strong>
                    <ul>
                        <li><a href="">Characers</a></li>
                        <li><a href="">Comics</a></li>
                        <li><a href="">Movies</a></li>
                        <li><a href="">TV</a></li>
                        <li><a href="">Games</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">News</a></li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="bottom-foot">
            <div class="container">
                <div class="btn-signup">
                    <a href="">SIGN-UP NOW!</a>
                </div>

                <div class="follow-other-platforms">
                    <strong>FOLLOW US</strong>
                    <a href="">
                        <img src="../assets/img/footer-facebook.png" alt="">
                    </a>
                    <a href="">
                        <img src="../assets/img/footer-twitter.png" alt="">
                    </a>
                    <a href="">
                        <img src="../assets/img/footer-youtube.png" alt="">
                    </a>
                    <a href="">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                    </a>
                    <a href="">
                        <img src="../assets/img/footer-periscope.png" alt="">
                    </a>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterComp'
}
</script>

<style lang="scss" scoped>
    footer .top-foot{
        background-image: url('../assets/img/footer-bg.jpg');
        height: 400px;
    }

    .col-sx, .col-center, .col-dx{
        float: left;
        margin-right: 40px;

        display: flex;
        flex-direction: column;
        color: white;

        strong{
            margin-top: 30px;
            margin-bottom: 15px;
            font-size: 1.3rem;
        }

        li{
            margin-top: 8px;
        }

        li a{
            color: #949496;

            &:hover{
                color: white;
                text-decoration: underline;
            }
        }
    }
    

    .bottom-foot{
        height: 100px;
        background-color: #2d2d2d;

        .container{
            display: flex;
            justify-content: space-between;
        }

        .btn-signup, .follow-other-platforms{
            display: flex;
            align-items: center;
        }

        .btn-signup{
            a{
                padding: 10px;
                color: white;
                border: 2px solid #0081f9;
            }
        }

        .follow-other-platforms{
            strong{
                color: #0081f9;
            }

            a{
                margin-left: 20px;

                img{
                    height: 40px;
                }
            }
        }
    }
</style>