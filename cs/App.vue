<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  created() {
    this.$store.dispatch('getUserInformation')
  },
}
</script>

<style>
body,
#app {
  margin: 0;
  padding: 0;
  height: 100%;
  min-width: 1200px;
}
</style>
