<script>
export default {
    
}
</script>
<template>
    <div>
        <button>Load More</button>
    </div>
</template>
<style lang="scss" scoped>
@use '../style/partials/mixin';
@use '../style/partials/variables';

div{
    background-color: variables.$bg-main;
    display: flex;
    justify-content: center;
    padding-bottom: 1.2rem;
}
button{
    font-size: 0.7rem;
    font-weight: 500;
    font-family: sans-serif;
    text-transform: uppercase;
    color: white;
    background-color: variables.$bg-topFooter;
    border: none;
    padding: 0.6rem 1.8rem;
}

</style>