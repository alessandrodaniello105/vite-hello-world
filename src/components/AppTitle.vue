<script>

// 2. Create AppTitle.Vue, create a string as title, style it and add in template

export default {

  name: 'AppTitle',

  data(){
    return {
      title: 'La mia prima app con Vite!'
    }
  }

}

</script>

<template>

  <h1>{{ title }}</h1>

</template>

<style scoped>

  h1 {
    color: white;
    text-align: center;
  }

</style>