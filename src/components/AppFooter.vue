
<script>
import TopFooter from './TopFooter.vue';
import MainFooter from './mainfooter.vue';
import BottomFooter from './BottomFooter.vue';

export default {
    section:'appFooter',
    components: {
        TopFooter,
        MainFooter,
        BottomFooter
    }
}
</script>
<template>
    <div>
        <TopFooter/>
        <MainFooter/>
        <BottomFooter/>  
    </div>
</template>
<style lang="scss" scoped>
    @use '../style/partials/variables'; 
    @use '../style/partials/mixin';

</style>