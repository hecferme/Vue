<template>
  <div id="app">
    <Docs v-bind:items="items"/>
  </div>
</template>

<script>
import  Docs from './components/Docs';

export default {
  name: 'App',
  components: {
    Docs
  }, 
  data: () => 
  { 
    return { 
      items: 
      [ 
        { 
          id: 1, 
          name: "Test 1", 
          exp: "16 Oct 2022" 
        },
        { 
          id: 2, 
          name: "Test 2", 
          exp: "16 Nov 2021" 
        } 
      ]
    }
  }
}
</script>

<style>

</style>
