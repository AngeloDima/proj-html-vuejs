<template>
  <div id="app">
    <header_cli />
    <section_one />
    <section_two />
    <section_three />
  </div>
</template>

<script>
import header_cli from '/src/components/header_cli.vue'
import section_one from '/src/components/section_one.vue'
import section_two from '/src/components/section_two.vue'
import section_three from '/src/components/section_three.vue'

export default {
  name: 'App',
  components: {
    header_cli,
    section_one,
    section_two,
    section_three,
}
}
</script>

<style lang="scss">


</style>
