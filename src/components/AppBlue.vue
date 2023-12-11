<script>
export default{
    data(){
        return{
            blueList:[
               
                {
                    image:"../src/assets/imgs/buy-comics-digital-comics.png",
                    link:"digital comics"
                },
                {
                    image:"../src/assets/imgs/buy-comics-merchandise.png",
                    link:"dc merchandise"
                },
                {
                    image:"../src/assets/imgs/buy-comics-subscriptions.png",
                    link:"subscription"
                },
                {
                    image:"../src/assets/imgs/buy-comics-shop-locator.png",
                    link:"comic shop locator"
                },
                {
                    image:"../src/assets/imgs/buy-dc-power-visa.svg",
                    link:"dc power visa"
                }
            ]
        }
    }
}
</script>
<template>
<div class="blue">
<ul>
    <li v-for="item in blueList">
    <img :src="item.image" alt="item.link">
    <a href="">{{ item.link.toUpperCase() }}</a></li>
</ul>
</div>
</template>
<style scoped lang="scss">
.blue{
    height: 155px;
    background-color: #0282f9;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    ul{
        display: flex;
        align-items: center;
        justify-content: space-around;
        list-style: none;
        gap: 10px;

        li{ display: flex;
            align-items: center;
            gap: 10px;
            img{
                width: 37px;
            }
            a{
                text-decoration: none;
                color: white;
            }
        }
        li:nth-child(4) img{
            width: 27px;
        }
        li:first-child img{
            width: 30px;
        }
    }
}

</style>