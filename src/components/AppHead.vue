<script>
export default {
    data() {
        return {
            toplist: [
                characters,
                comics,
                movies,
                tv,
                games,
                collectibles,
                videos,
                fans,
                news,
                shop


            ]
        }
    }
}
</script>
<template>
    <div class="header-container">
        <img src="../assets/imgs/dc-logo.png" alt="DC Logo Small">
        <ul>
            <li v-for="item in toplist">{{ item.toUpperCase() }}</li>
        </ul>
    </div>
</template>
<style lang="scss">
.header-container {
    height: 120px;
    border-bottom: 1px solid;
    display: flex;

}
</style>