
<script>
import AppTitle from './components/AppTitle.vue';
import AppJumbotron from './components/AppJumbotron.vue';
export default {
  data() {
    return {

    }
  },
  components: {
    AppTitle,
    AppJumbotron
  }
}
</script>

<template>
  <AppTitle />
  <AppJumbotron />
</template>

<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
