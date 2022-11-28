<template>
  <div>
    <h3>{{ msg }}</h3>
  </div>
</template>

<script>
  export default {
    name: 'MyComponent',
    props: {
      msg: String
    }
  }
</script>

<style lang="scss" scoped>
  h3 {
    color: blue
  }
</style>