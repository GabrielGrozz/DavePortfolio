<script setup>
const props = defineProps({
    direction: String
})

</script>

<template>
    <div :class="'project'+direction">
        <div class="project-about">
            dale
        </div>
    </div>
</template>

<style scoped>
.project1 {
    display: flex;
    padding: 50px 150px;
    background: rgb(255, 188, 197);
    background-color: blue;
  }
  .project2 {
    display: flex;
    justify-content: flex-end;
    padding: 10px 150px;
    background: rgb(255, 49, 77);
    background: rgb(224, 232, 0);
  }



</style>