<script setup>
const name = 'hridoy'
</script>

<template>
  <h1>hello world</h1>
  <p>Using text interpolation: {{ name }}</p>
  <p>Using v-html directive: <span v-html="rawHtml"></span></p>
</template>
