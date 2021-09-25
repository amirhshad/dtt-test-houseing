<template>
  <div id="app">
    <div class="content">
      <div class="top-bar">
        <Navigation />
      </div>
      <div class="container">
        <Header />
      </div>
    </div>
  </div>



</template>

<script>

import Header from './components/Header'
import Navigation from './components/Navigtion'

export default {
  name: 'App',
  components: {
    Navigation,
    Header,
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Poppins', sans-serif;
}
.container {
  max-width: auto;
  margin: 30px auto;
  overflow: auto;
  min-height: 300px;
  border: 1px solid steelblue;
  padding: 30px;
  border-radius: 5px;
}

.btn {
  display: inline-block;
  background: #000;
  color: #fff;
  border: none;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
}
</style>
