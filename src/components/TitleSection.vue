<script setup lang="ts">
// This is how you pass in props.
defineProps<{
  text: string,
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ text }}</h1>
    <p>lets hope this isn't a tie...</p>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 5rem;
  position: relative;
  text-shadow: 3px 2px #676767;
  text-decoration: underline;
  stroke: 5px #444444;
  margin: 0;
  margin-top: 5rem;
  padding: 0;
}

.greetings h1,
.greetings p {
  text-align: center;
}

p {
  font-size: 1.5rem;
}
</style>
