  
<template>
  <div id="app">
    {{ message }}
  </div>
</template>

<script>  
  var app = new Vue({
    el: '#app',
    data: {
      message: 'Hello Vue World!'
    }
  })
</script>  

<style>
  p {
    font-size: 2em;
  }
</style>
