<script setup>
defineProps({
  text: {
    type: String,
    required: true
  }
})
</script>

<template>
  <button class="button btn dfgfg">
    {{ text }}
  </button>
</template>

<style scoped>
button {
  padding: 2px;
}
</style>
