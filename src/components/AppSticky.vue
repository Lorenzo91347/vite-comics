<script>
export default {}
import { library } from '@fortawesome/fontawesome-svg-core'
</script>
<template>
    <div class="sticky-back">
        <div class="sign-up">SIGN UP NOW!</div>
        <div class="social">
            <div>FOLLOW US</div>
            <div class="icons">
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-youtube"></i>
                <i class="fa-brands fa-pinterest-p"></i>
                <i class="fa-solid fa-location-dot"></i>
            </div>
        </div>
    </div>
</template>
<style scoped lang="scss">
.sticky-back{
    height: 105px;
    background-color: #303030;
    display: flex;
    justify-content: space-around;
    align-items: center;
    .sign-up{
        border: 3px solid #0282f9;
        height: 15px;
        color: white;
        padding: 15px;
    }
    .social{
        display: flex;
        align-items: center;
        div{
            margin-right: 15px;
        }
        .icons{
            display: flex;
            gap: 5px;
            i{
                text-align: center;
                line-height: 30px;
                background-color: #797979;
                color: #303030;
                width: 30px;
                height: 30px;
                border-radius: 15px;
            }
        }

    }
}</style>