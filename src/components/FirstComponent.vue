<template>
  <div>
    <h3>{{ msg }}</h3>
  </div>
</template>

<script>
  export default {
    name: 'FirstComponent',
    props: {
      msg: String
    }
  }
</script>

<style lang="scss" scoped>

</style>