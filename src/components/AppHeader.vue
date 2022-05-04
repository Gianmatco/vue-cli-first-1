<template>
  <div>
    <h1>Questa è una prova</h1>
     <img :src="img" alt="">
  </div>
</template>

<script>
export default {
  name: 'AppHeader',
  data(){
    return {
        img: './images/logo.png'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  color: red;
}

</style>
