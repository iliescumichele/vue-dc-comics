<template>
    <header class="dbg">
        <div class="container dbg">
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

            .logo img{
                height: 90%;
            }
        }

        .nav ul{
            display: flex;
            flex-direction: row;

            li{
                list-style: none;
                margin: 10px 15px;
                vertical-align: middle;
                line-height: 67px;
                font-weight: bold;
                a{
                    text-decoration: none;
                    color: black;
                }
            }

            li.active{
                border-bottom: 3px solid #017bec;
            }
        }
    }


</style>