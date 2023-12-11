<script>
export default{
    data(){
        return{
            blueList:[
               
                {
                    image:"../assets/imgs/buy-comics-digital-comics.png",
                    link:"digital comics"
                },
                {
                    image:"../assets/imgs/buy-comics-merchandise.png",
                    link:"dc merchandise"
                },
                {
                    image:"../assets/imgs/buy-comics-subscriptions.png",
                    link:"subscription"
                },
                {
                    image:"../assets/imgs/buy-comics-shop-locator.png",
                    link:"comic shop locator"
                },
                {
                    image:"../assets/imgs/buy-dc-power-visa.svg",
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
    <img src="" alt="item.link">
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
        li{
            a{
                text-decoration: none;
                color: white;
            }
        }
    }
}

</style>