<script setup>
defineProps({
  label: {
    type: String,
    required: true,
  }
})
</script>

<template>
  <a>{{ label }}</a>
</template>

<style scoped>
a {
  padding: 8px 16px;
  background: darkslategrey;
  border-radius: 8px;
  user-select: none;
  cursor: pointer;
  transition: 200ms all;
  font-weight: 600;
  font-size: 16px;
}

a:hover {
  background: lightslategray;
}
</style>