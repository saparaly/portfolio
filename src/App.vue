<script setup>
import SidebarVue from "./components/Sidebar.vue";
import Navbar from "./components/Navbar.vue";
import ContentVue from "./components/Content.vue";
</script>

<template>
  <div class="flex">
    <SidebarVue/>
    <ContentVue/>
    <Navbar/>
  </div>
</template>

<style lang="scss">
</style>
