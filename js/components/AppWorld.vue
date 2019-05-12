<template>
  <span>World</span>
</template>

<script>
module.exports = {
  mounted () {
    console.dir('Hello World')
  }
}
</script>

<style scoped>
  span {
    background-color: yellow;
  }
</style>