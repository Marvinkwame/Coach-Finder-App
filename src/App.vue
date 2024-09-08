<template lang="">
  <div>
    <the-nav></the-nav>
  </div>
  <main>
    <router-view></router-view>
  </main>
</template>

<script>
import TheNav from './components/layout/TheNav.vue';

export default {
  components: {
    TheNav,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>
