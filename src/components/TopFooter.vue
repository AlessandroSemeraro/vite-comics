<script>
export default {
    
}
</script>
<template>
    <section class="topFooter">
       <div class="topFooter-container">
            <ul>
                <li><img src="../../vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="logo phone dc comics"><p>Digital comics</p></li>
                <li><img src="../../vue-dc-comics-1/img/buy-comics-merchandise.png" alt="logo merchandise dc comics"><p>DC merchandise</p></li>
                <li><img src="../../vue-dc-comics-1/img/buy-comics-subscriptions.png" alt="logo subscription dc comics"><p>Subscription</p></li>
                <li><img class="point-size" src="../../vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="logo locator shop dc comics"><p>Comic Shop Locator</p></li>
                <li><img src="../../vue-dc-comics-1/img/buy-dc-power-visa.svg" alt=""><p>DC Power Visa</p></li>
            </ul>
       </div> 
    </section>
</template>
<style lang="scss" scoped>
    @use '../style/partials/variables';
    @use '../style/partials/mixin';

    ul{
        width: variables.$full-width;
        list-style-type: none;
        display: flex;
        justify-content: space-around;
    }

    li{
        color: white;
        text-transform: uppercase;
        font-family: sans-serif;
        font-size: 0.8rem;
        display: flex;
        align-items: center;
    }

    img{
        width: 2.5rem;
        margin-right: 0.7rem;
    }
    img.point-size{
        width: 1.8rem;
    }
    
    .topFooter{
        position: relative;
        z-index: 5;
        height: 10rem;//17vh
        width: 100%;
        background-color: variables.$bg-topFooter;
        display: flex;
        justify-content: center;
        
        .topFooter-container{
            width: variables.$container-width;
            display: flex;
            align-items: center;
        }
    }
</style>