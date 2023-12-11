<script>
export default{
    props:[ "thumb","series"]
}
</script>
<template>
         <div class="comic">
            <img :src="thumb" :alt="series">
            <h4>{{ series }}</h4>
        </div>
</template>
<style lang="scss" scoped>
.comic{
    color: white;
    width: calc(100%/6);
    display: flex;
    flex-direction: column;
    
}
img{
       max-width: 185px;
       max-height: 185px;
       object-fit: cover;
            
        }
</style>