<script>
export default {
    data() {
        return {
            toplist: [
                'characters',
                'comics',
                'movies',
                'tv',
                'games',
                'collectibles',
                'videos',
                'fans',
                'news',
                'shop'


            ]
        }
    }
}
</script>
<template>
    <div class="header-container">
        <img src="../assets/imgs/dc-logo.png" alt="DC Logo Small">
        <ul>
            <li v-for="item in toplist"><a href="">
                    {{ item.toUpperCase() }}
                </a></li>
        </ul>
    </div>
</template>
<style scoped lang="scss">
$merch_color: #0282f9;

.header-container {
    height: 120px;
    display: flex;
    justify-content: space-around;
    align-items: center;

    img {
        height: 80px;
    }

    ul {
        display: flex;
        gap: 10px;
        list-style: none;
        align-items: center;

        li {
            border-bottom: 5px black;

            a {
                font-size: 12px;
                text-decoration: none;
                color: black;

                &:hover {
                    padding-bottom: 47px;
                    color: #0282f9;
                    border-bottom: 5px solid;
                }
            }

        }

    }

}
</style>