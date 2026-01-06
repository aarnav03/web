
<template>
  <section>
    <h2 class="text-xl font-semibold mb-8">
      Work
    </h2>

    <div class="flex gap-8 overflow-x-auto pb-4">
      <ProjectCard v-for="n in 4" :key="n" />
    </div>
  </section>
</template>

<script setup>
import ProjectCard from "./proj.vue"
</script>
