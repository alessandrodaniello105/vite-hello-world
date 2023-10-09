<script>
// Bonus 2. Create AppHero.vue, name it, style it, add img in template
export default {
  
  name: 'AppHero'

}

</script>

<template>

  <div class="img-box">

    <img src="../assets/img/jumbotron.png" alt="jumbotron">

  </div>

</template>

<style scoped>

  .img-box {
    height: 80vh;
    text-align: center;
  }

  img {
    height: 100%;
    object-fit: cover;
  }

</style>