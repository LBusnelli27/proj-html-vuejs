<template>
  <div id="app">
    <Header />
    <Main />
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';

import Header from './components/Header.vue';
import Main from './components/Main.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700&family=Raleway:wght@100;200;300;400;500;600;700&display=swap');

#app {
  min-width: 1100px;
}
</style>
