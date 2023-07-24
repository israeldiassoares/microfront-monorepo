<template>
  <div class="home">
    <NavBar class="flex flex-row" :menu="['item 1', 'item 2', 'item 3']" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import NavBar from "@/components/NavBar.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    NavBar,
  },
});
</script>

<style>
.flex > nav {
  display: flex;
}

.flex .flex-row {
  display: flex;
  flex-direction: row;
}
</style>
