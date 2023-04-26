<script>
  export default {
  name:'AppTitle',
  data() {
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
  h1{
    color: whitesmoke;
  }

  @media (prefers-color-scheme: light) {
    h1{
    color: blue;
    }
  }
</style>
