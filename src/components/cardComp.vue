<template>
    <div class="card">
        <div class="card-img">
            <a href="">
                <img :src="cardData.thumb" :alt="cardData.series">
            </a>
        </div>
        <a href=""><p>{{cardData.series}}</p></a>
    </div>
</template>

<script>
export default {
    name: 'cardComp',
    props: {
        cardData: Object
    }
}
</script>

<style lang="scss" scoped>
    .card{
        margin: auto 10px; 
        width: 200px;
        

        .card-img{
                img{
                    object-fit: cover;
                    width: 100%;
                }
            }
            
            p{
                margin: 10px auto;
                color: white;
            }
                    
    }
</style>