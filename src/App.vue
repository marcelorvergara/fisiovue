<template>
  <div id="app">
    <menu-bar></menu-bar>
  </div>
</template>

<script>

import Menu from "@/components/Menu";
export default {
  name: 'App',
  components: {
    menuBar: Menu
  }
}
</script>

<style>
.bg-company-green{
  background: rgba(12, 177, 75, 1.0); /* fallback for old browsers */
  background: -webkit-linear-gradient(right, rgba(12, 177, 75, 1.0), #8DC26F);
  background: -moz-linear-gradient(right, rgba(12, 177, 75, 1.0), #8DC26F);
  background: -o-linear-gradient(right, rgba(12, 177, 75, 1.0), #8DC26F);
  background: linear-gradient(to left, rgba(12, 177, 75, 1.0), #8DC26F);
  font-weight: bolder;
  color: white;
}
</style>
