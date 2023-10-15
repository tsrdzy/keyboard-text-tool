<template>
  <main>
    <yn_header></yn_header>
    <yn_main></yn_main>
  </main>
</template>

<script>
import yn_header from './components/yn_header.vue';
import yn_main from './components/yn_main.vue';
export default {
  name: 'App',
  components: {
    yn_header,
    yn_main
  }
}
</script>

<style lang="less" scoped>
</style>
