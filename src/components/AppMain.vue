
<script>
import MainJumbotron from './MainJumbotron.vue';
import ListDc  from './ListDc.vue';

export default {
    section:'appMain',
    components: {
        MainJumbotron,
        ListDc
    }
}

</script>
<template>
    <body>
        <MainJumbotron/>
        <div class="albums">
            <ListDc/>
        </div>
    </body>
</template>
<style lang="scss" scoped>
   @use '../style/partials/mixin';
   @use '../style/partials/variables'; 


    .albums{
        height: 100%;//15vh
        width: 100%;
        background-color: variables.$bg-main;
        display: flex;
        justify-content: center;
        align-items: center;
        padding:3rem 0 6rem 0;
    }
</style>