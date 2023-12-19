<template>
  <Button>
    <p>Hello</p>
  </Button>
  <Button>
    <span>CLick</span>
    <img src="https://picsum.photos/seed/picsum/200/300" alt="logo">
  </Button>
</template>

<script>
import Button from './components/Button.vue';


export default {
  name: 'App',
  components: {
    Button
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
