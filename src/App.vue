<template>
  <div id="app">
    <header_cli />
    <section_one />
  </div>
</template>

<script>
import header_cli from '/src/components/header_cli.vue'
import section_one from '/src/components/section_one.vue'

export default {
  name: 'App',
  components: {
    header_cli,
    section_one
}
}
</script>

<style lang="scss">


</style>
