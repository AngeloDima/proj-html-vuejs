<template>
  <div id="app">
    <header_cli />
    <section_one />
    <section_two />
    <section_three />
    <section_four />
    <section_five />
    <section_six />
    <section_seven />
    <section_eight />
    <section_nine />
    <footer_cli />
  </div>
</template>

<script>
import header_cli from '/src/components/header_cli.vue'
import section_one from '/src/components/section_one.vue'
import section_two from '/src/components/section_two.vue'
import section_three from '/src/components/section_three.vue'
import section_four from './components/section_four.vue'
import section_five from './components/section_five.vue'
import section_six from './components/section_six.vue'
import section_seven from './components/section_seven.vue'
import section_eight from './components/section_eight.vue'
import section_nine from './components/section_nine.vue'
import footer_cli from './components/footer_cli.vue'

export default {
  name: 'App',
  components: {
    header_cli,
    section_one,
    section_two,
    section_three,
    section_four,
    section_five,
    section_six,
    section_seven,
    section_eight,
    section_nine,
    footer_cli,
}
}
</script>

<style lang="scss">
*{
    
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }

</style>
