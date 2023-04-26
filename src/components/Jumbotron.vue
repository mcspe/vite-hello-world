<script>
export default {
  name:'Jumbotron',
  data() {
    return {
      imgSrc: '../src/assets/jumbo.jpg',
      imgAlt: 'Jumbotron'
    }
  }
}
</script>

<template>
  <div>
    <img :src="imgSrc" :alt="imgAlt">
  </div>
</template>  

<style scoped>
  div{
    border-radius: 1.5rem;
    box-shadow: 0 0 1.5rem whitesmoke;
    overflow: hidden;
  }

  img{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  @media (prefers-color-scheme: light) {
    div{
    box-shadow: 0 0 .5rem .5rem lightskyblue;
    }
  }
</style>