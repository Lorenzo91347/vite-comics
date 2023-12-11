<script>
export default {
    data(){
        return{
            dcComics:[
                "Characters",
                "Comics",
                "Movies",
                "TV",
                "Games",
                "Videos",
                "News"
            ],
            shop:[
                "Shop DC",
                "Shop DC Collectibles",
            ],
            dc:[
                "Terms of Use",
                "Privacy Policy(New)",
                "Ad Choices",
                "Advertising",
                "Jobs",
                "Subscriptions",
                "Talent Workshops",
                "CPSC Certificates",
                "Ratings",
                "Shop Help",
                "Contact Us"
            ],
            sites:[
                "DC",
                "MAD Magazine",
                "DC Kids",
                "DC Universe",
                "DC Power Visa"
            ]
        }
    }
}
</script>
<template><div class="foot-background">
<div>
    <div>
        <div class="special">
            
            <ul >
                <h4>DC COMICS</h4>
                <li v-for="item in dcComics"><a href="">{{ item }}</a></li>
            </ul>
            <ul>
                <h4>SHOP</h4>
                <li v-for="item in shop"><a href="">{{ item }}</a></li>
            </ul>
        </div>
       
        <div>
           
            <ul>
                <h4>DC</h4>
                <li v-for="item in dc"><a href="">{{ item }}</a></li>
            </ul>
        </div>
        <div>
            
            <ul>
                <h4>SITES</h4>
                <li v-for="item in sites"><a href="">{{ item }}</a></li>
            </ul>
        </div>
    </div>
     
    </div>
    
    <img src="../assets/imgs/dc-logo-bg.png" alt="">
    
</div>
</template>
<style scoped lang="scss">
.foot-background {
    background-image: url(../assets/imgs/footer-bg.jpg);
    height: 370px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    div{
        
        
        display: flex;
        flex-wrap: wrap;
      .special{
        display: flex;
        flex-direction: column;
      }
     
        
    }
    ul{
        list-style: none;
         h4{
            color: white;
        }
        li{
            a{
                text-decoration: none;
                color: grey;
            }
        }
    }
    
      
        img{
       
            width: 430px;
            height: 430px;
            object-fit: cover;
            clip-path: inset(30px 0 );
        }
    
}
</style>