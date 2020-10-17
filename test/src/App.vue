<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App and Cartaguito Campeón"/>
    <Docs v-bind:items="items"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Docs from './components/Docs'

export default {
  name: 'app',
  components: {
    HelloWorld, 
    Docs
  },
  data: () => {
    return {
      items: [
        {
          id: 1,
          name: "Test 1",
          exp: "16 Oct 2019"
        },
        {
          id: 2,
          name: "Test 2",
          exp: "16 Nov 2019"
        }
      ]
    }
  }
}
</script>

<style>

</style>
