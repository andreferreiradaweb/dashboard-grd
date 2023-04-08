<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from '@/components/VHeader/VHeader.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
  @import './styles.scss';
</style>
