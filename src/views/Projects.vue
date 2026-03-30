<script setup>
import projects from '../Projects.json'
</script>

<template>
<div>
  <h1>Projects</h1>
    <ul>
      <li v-for="project in projects" :key="project.name">
          {{project.name }}
      </li>
    </ul>
</div>
</template>

<style scoped>

</style>