<script>

export default {
    name: 'albumDCElement',
    props: [
        'thumbSrcDc',
        'priceDc',
        'seriesDc',
        'typeDc',
]
}
</script>

<template>
    <article>
        <div class="wrapper-img">
            <img :src="thumbSrcDc" alt="album logo">
        </div>
        <p>{{ seriesDc }}</p>
    </article>
</template>

<style lang="scss" scoped>
@use '../style/partials/variables';
@use '../style/partials/mixin';

p{
    text-transform: uppercase;
    font-family: sans-serif;
    color: white;
    margin-top: 0.75rem;
    font-size: 0.8rem;
}

article {
    width: calc((100% / 6) - 0.8rem);
    height: 12rem;
    margin-right: 0.8rem;
    display: flex;
    flex-wrap: nowrap;
    margin-bottom: 1rem;
    display: flex;
    flex-direction: column;

    .wrapper-img {
        width: 100%;
        height: 9rem;
        display: flex;
        flex-direction: column;
        align-items: center;
        
        img{
            width: 100%;
            height: 100%;
        }
       
    }
}
</style>