<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';

import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700&family=Raleway:wght@100;200;300;400;500;600;700&display=swap');

#app {
  min-width: 1100px;
}
</style>
