<template>
    <div class="links-before-footer">
        <div class="container">
            <div class="link">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="">DIGITAL COMICS</a>
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <a href="">DC MERCHANDISE</a>

            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <a href="">SUBSCRIPTION</a>
                
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <a href="">COMIC SHOP LOCATOR</a>

            </div>
            <div class="link">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <a href="">DC POWER VISA</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'LinksBeforeFooterComp'
}
</script>

<style lang="scss" scoped>
    .links-before-footer{
        height: 150px;
        background-color: #0081f9;

        .container{
            display: flex;
            justify-content: space-evenly;
        }
    }

    .link{
        display: flex;
        align-items: center;

        a{
            color: white;
            margin: 15px;
        }

        img{
            height: 40%;
        }
    }
</style>