<template>
  <div class="content">
    <BannerComponentVue/>
    <WorkComponentVue/>
    <EduComponentVue/>
    <ProjectsComponentVue/>
    <!-- <FooterVue/> -->
  </div>
</template>

<script setup>
import BannerComponentVue from "./BannerComponent.vue";
import EduComponentVue from "./EduComponent.vue";
// import FooterVue from "./Footer.vue";
import ProjectsComponentVue from "./ProjectsComponent.vue";
import WorkComponentVue from "./WorkComponent.vue";
</script>


<style scoped lang="scss">
.content {
    width: 100%;
    margin: 0 50px;
}

</style>