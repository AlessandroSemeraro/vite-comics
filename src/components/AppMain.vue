
<script>
import ListDc  from './ListDc.vue'

export default {
    section:'appMain',
    components: {
        ListDc
    }
}

</script>
<template>
    <body>
        <main class="albums">
            <ListDc/>
        </main>
    </body>
</template>
<style lang="scss" scoped>
   @use '../style/partials/mixin';
   @use '../style/partials/variables'; 

    .albums{
        height: 8rem;//15vh
        width: 100%;
        background-color: variables.$bg-main;
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>