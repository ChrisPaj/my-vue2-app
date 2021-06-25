<template>
  <div>
    <app-shell></app-shell>
  </div>
</template>

<script>
  import Vue from 'vue';
  import AppShell from './components/AppShell/AppShell.vue'
  export default Vue.extend({
    name: 'app',
    components: { AppShell },
  });
</script>

<style scoped></style>
