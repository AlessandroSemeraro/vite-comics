
<script>
export default {
    section: 'appHeader'
}
</script>
<template lang="">
    <header>
        <div class="container-header">
            <img class="img-dc-logo" src="C:\Users\alese\OneDrive\Desktop\Boolean\js\vite-comics\vue-dc-comics-1\img\dc-logo.png" alt="logo DC">
            <ul class="MyNav">
                <li>Characters <div class="blue-hover"></div></li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>
        </div>
    </header>
</template>
<style lang="scss" scoped>
@use '../style/partials/variables';
@use '../style/partials/mixin';



header {
    height: 8rem; //15vh
    width: 100%;
    background-color: variables.$bg-header;
    display: flex;
    justify-content: center;
    align-items: center;

    div.container-header {
        width: variables.$container-width;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;

        .img-dc-logo {
            width: 5.5rem;
        }

        .MyNav {
            display: flex;
            list-style-type: none;

            li {
                margin-right: 1rem;
                font-size: 0.7rem;
                color: rgb(64, 64, 64);
                font-weight: bolder;
                text-transform: uppercase;
                font-family: sans-serif;
                position: relative;
                

                &:hover {
                    color: variables.$bg-topFooter;
                    
                }
            }
        }
    }
}</style>