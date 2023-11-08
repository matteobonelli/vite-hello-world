<template>
  <div>
    <AppTitle />
    <AppHero />
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'

export default {
  components: { AppTitle, AppHero }
}
</script>
  
<style lang="css" scoped>
div {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>