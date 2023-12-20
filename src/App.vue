<script>
import AppHeader  from './components/appHeader.vue'
import AppMain  from './components/AppMain.vue'
import AppFooter  from './components/appFooter.vue'


export default {
  components:{
    AppHeader,
    AppMain,
    AppFooter
  }
}

</script>

<template>
  <AppHeader/>
  <AppMain/>
  <AppFooter/>
 
</template>

<style lang="scss">
@use './style/general.scss' as *;

</style>
