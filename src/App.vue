<template>
  <div id="app">
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>
import PageHeader from '@/components/PageHeader.vue';
import PageBody from '@/components/PageBody.vue';
import PageFooter from '@/components/PageFooter.vue';

export default {
  name: 'App',
  components: {
    PageHeader,
    PageBody,
    PageFooter
  }
}
</script>

<style>
#app {
  display: grid;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
