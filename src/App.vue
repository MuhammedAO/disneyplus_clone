<template>
  <div id="app" class="bg-gray-900 flex text-white min-h-screen">
    <SideBarNav />

    <div class="w-full">
      <transition name="page" mode="out-in">
        <router-view />
      </transition>
    </div>
  </div>
</template>

<script>
// import { Slide } from "vue-burger-menu";
import SideBarNav from "./components/SideBarNav";
export default {
  components: {
    // Slide
    SideBarNav
  }
};
</script>

<style src="./css/main.css"></style>
