<script>

export default {

  name: 'AppTitle',

  data(){
    return {
      titolo: 'La mia prima app con Vite!'
    }
  }
  
}

</script>

<template>

  <h1>{{ titolo }}</h1>

</template>

<style scoped>

  h1 {
    color: white;
    text-align: center;
  }

</style>