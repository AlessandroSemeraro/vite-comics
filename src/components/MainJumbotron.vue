<script>
export default {
   name:'jumbotronDC' 
}
</script>
<template>
    <div class="wrapper-jumbotron">
        <img src="../../vue-dc-comics-1/img/jumbotron.jpg" alt="jumbotronDC">
    </div>
</template>
<style lang="scss" scoped>
    @use '../style/partials/variables';
    @use '../style/partials/mixin';

.wrapper-jumbotron{
    width: 100%;
    height: 25rem;
    img{
    object-fit: cover;
    object-position: top 0 right 0;
    width: 100%;
    height: 100%;
    }
}

</style>