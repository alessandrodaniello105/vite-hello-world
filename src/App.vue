<script>

  // 3. Import AppTitle in App.vue
  import AppTitle from './components/AppTitle.vue'

  // Bonus 3. Import AppHero in App.vue
  import AppHero from './components/AppHero.vue'

  export default {

    name: 'App',

    // 4. Add AppTitle as components
    // Bonus 4. Add AppHero as components
    components:{
      AppTitle,
      AppHero
    }

  }

</script>

<template>

  <!-- Bonus 5. Invoke AppHero in template -->
  <AppHero />

  <!-- 5. Invoke AppTitle in template -->
  <AppTitle />

</template>

<style scoped>
  body {
    text-align: center;
  }
</style>
