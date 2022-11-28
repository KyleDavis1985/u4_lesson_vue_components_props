<template>
  <div>
    <h3> {{ msg }} </h3>
  </div>
</template>

<script>
  export default {
    name: 'SecondComponent',
    props: ['msg'],
    msg: {
      type: String
    }
  }
</script>

<style lang="scss" scoped>

</style>