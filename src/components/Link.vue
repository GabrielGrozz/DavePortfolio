<script setup>
const props = defineProps({
  name: String,
  img: String,
  link: String,
});
</script>

<template>
  <a :href="link" class="flex link">
    <img :src="img" alt="name" class="links-image" />
    <p>{{name}}</p>
  </a>
</template>

<style scoped>

.link{
    align-items: center;
    margin: 0 15px;
}
.links-image {
  height: auto;
  width: auto;
  max-width: 30px;
  max-height: 30px;
  margin: 0 3px;
}
</style>
