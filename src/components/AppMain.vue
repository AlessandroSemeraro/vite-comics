
<script>
import MainJumbotron from './MainJumbotron.vue';
import ListDc from './ListDc.vue';
import MainButtonLoad from './MainButtonLoad.vue';

export default {
    section: 'appMain',
    components: {
        MainJumbotron,
        ListDc,
        MainButtonLoad
    }
}

</script>
<template>
    <body>
        <MainJumbotron />
        <div class="albums">
            <h2>Current series</h2>
            <ListDc />
        </div>
        <MainButtonLoad />
            
    </body>
</template>
<style lang="scss" scoped>
@use '../style/partials/mixin';
@use '../style/partials/variables';

h2 {
    font-size: 1.4rem;
    font-weight: 500;
    font-family: sans-serif;
    text-transform: uppercase;
    color: white;
    background-color: variables.$bg-topFooter;
    border: none;
    padding: 0.75rem 0.9rem;
    position: absolute;
    top: -1.5rem;
    left: 15rem;
}

.albums {
    height: 100%; //15vh
    width: 100%;
    background-color: variables.$bg-main;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 3rem 0 2rem 0;
    position: relative;
}
</style>