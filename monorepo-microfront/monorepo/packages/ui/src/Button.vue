<template>
    <button>
        {{ props.label }}
    </button>
</template>
<script setup lang="ts">
const props = defineProps(
    {
        label: String
    })
</script>

<style>
button {
    margin: 12px;
    padding: 12px;
    background-color: green;
    border-radius: 10rem;
    width: 120px;
}
</style>