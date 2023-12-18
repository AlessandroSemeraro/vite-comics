
<script>
export default {
    name: 'listDc',
    data() {
        return {
            ListDc: []
        }
    },
}
</script>
<template >
    <div class="container-dc">
        <p class="text-main">--- Content goes here ---</p>
    </div>
</template>
<style lang="scss" scoped>
@use '../style/partials/mixin';
@use '../style/partials/variables';


.container-dc {
    width: variables.$container-width;
    

    .text-main {
        color: variables.$text-color-main;
        font-size: 2rem;
    }
}
</style>