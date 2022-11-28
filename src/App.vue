<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <MyComponent msg="This is my component!" />
    <FirstComponent msg="This is my First Component"/>
    <SecondComponent msg="This is an array?"/>
  </div>
</template>

<script>
import MyComponent from './components/MyComponent.vue';
import FirstComponent from './components/FirstComponent.vue';
import SecondComponent from './components/SecondComponent.vue';
export default {
  name: 'App',
  components: {
    MyComponent,
    FirstComponent,
    SecondComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

