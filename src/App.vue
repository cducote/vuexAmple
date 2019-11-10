<template>
  <div id="app">
    <Form/>
    <Display/> 
    
  </div>
</template>

<script>
import Form from './components/Form'
import Display from './components/Display'
// import DisplayTwo from './components/DisplayTwo'

export default {
  name: "App",
  components: {
    Form,
    Display,
    // DisplayTwo
  }
};
</script>

<style>

</style>
