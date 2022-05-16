<template>
    <header class="">
        <div class="container ">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="nav">
                <ul>
                    <li><a href=""> CHARACTERS</a></li>
                    <li class="active"><a href=""> COMICS</a></li>
                    <li><a href=""> MOVIES</a></li>
                    <li><a href=""> TV</a></li>
                    <li><a href=""> GAMES</a></li>
                    <li><a href=""> COLLECTIBLES</a></li>
                    <li><a href=""> VIDEOS</a></li>
                    <li><a href=""> FANS</a></li>
                    <li><a href=""> NEWS</a></li>
                    <li><a href=""> SHOP</a></li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderComp'
}
</script>

<style lang="scss" scoped>
    

    header{
        .container{
            height: 80px;
            display: flex;
            justify-content: space-between;

            .logo{
                display: flex;
                align-items: center;
            }
            .logo img{
                height: 85%;
            }
        }

        .nav ul{
            display: flex;
            flex-direction: row;

            li{
                margin: 8px 15px;
                vertical-align: middle;
                line-height: 67px;
                font-weight: bold;
                a{
                    color: black;
                }
            }

            li.active{
                border-bottom: 5px solid #017bec;
            }
        }
    }


</style>