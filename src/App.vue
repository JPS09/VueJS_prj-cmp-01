<template>
  <the-header title="Good places to learn"></the-header>
  <the-resources ></the-resources>
</template>

<script>
import TheResources from './components/learning-resources/TheResources';
export default {
  components: {
    TheResources
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
