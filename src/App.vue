<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <SideMenu />
    </div>
    <div class="column is-three-quarter">
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import SideMenu from "./components/SideMenu.vue";

export default defineComponent({
  name: "App",
  components: { SideMenu },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
