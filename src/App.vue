<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <!-- <Invitation /> -->
  <MoveIconButton />
</template>

<script>
// import Invitation from './components/Invitation.vue'
import MoveIconButton from './components/MoveIconButton.vue'

export default {
  name: 'App',
  components: {
    // Invitation,
    MoveIconButton
  }
}
</script>

<style>
html {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  font-size: 62.5%;
}
#app {
  height: 100vh;
  margin: 2em;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  display: flex;
  justify-content: center;
}

</style>
