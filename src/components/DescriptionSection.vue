<template>
  <div class="container" :style="{ alignItems: direction === 'left' ? 'start' : 'end' }">
    <p>{{ description1 }}</p>
    <p>{{ description2 }}</p>
  </div>
</template>
<script setup lang="ts">
defineProps({
  description1: String,
  description2: String,
  direction: String
})
</script>
<style scoped>
.container {
  color: black;
  padding: 60px 40px;
  background-color: #ffe8cd;
  display: flex;
  flex-direction: column;
  gap: 20px;

  p {
    font-family: 'Courier New', Courier, monospace;
    font-size: 16px;
    font-weight: bolder;
    text-align: justify;
    width: 60%;
  }
}

@media (max-width: 768px) {
  .container {
    justify-content: center;

    p {
      font-size: 12px;
      width: 100%;
    }
  }
}
</style>
