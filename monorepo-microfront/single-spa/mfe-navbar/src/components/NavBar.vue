<template>
  <div>
    <nav>
      <ul v-for="(item, index) in props.menu" :key="index">
        <li>{{ item }}</li>
      </ul>
    </nav>
  </div>
</template>

<script setup lang="ts">
const props = defineProps({
  menu: {
    type: Array,
    default() {
      return [];
    },
  },
});
</script>
