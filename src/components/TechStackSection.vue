<template>
  <section class="flex flex-col justify-center gap-8 max-w-6xl mx-auto p-4">
    <div class="grid grid-cols-1 sm:grid-cols-2 gap-8 bg-gray-700 rounded-2xl overflow-hidden shadow-2xl p-4">

      <!-- Frontend e SQL -->
      <div class="flex flex-col gap-4">
        <h3 class="text-lg font-bold text-gray-100">Frontend</h3>
        <div v-for="tech in frontendTechs" :key="tech.name">
          <span class="text-sm font-medium text-gray-300">{{ tech.name }}</span>
          <div class="flex items-center gap-0.5 mt-1">
            <span v-for="i in 10" :key="i" class="flex flex-1 h-2 rounded-md"
              :class="i <= tech.level ? 'bg-green-700' : 'bg-gray-900'"></span>
          </div>
        </div>

        <h3 class="text-lg font-bold text-gray-100 mt-6">SQL</h3>
        <div v-for="tech in sqlTechs" :key="tech.name">
          <span class="text-sm font-medium text-gray-300">{{ tech.name }}</span>
          <div class="flex items-center gap-0.5 mt-1">
            <span v-for="i in 10" :key="i" class="flex flex-1 h-2 rounded-md"
              :class="i <= tech.level ? 'bg-green-700' : 'bg-gray-900'"></span>
          </div>
        </div>
      </div>

      <!-- Backend -->
      <div class="flex flex-col gap-4">
        <h3 class="text-lg font-bold text-gray-100">Backend</h3>
        <div v-for="tech in backendTechs" :key="tech.name">
          <span class="text-sm font-medium text-gray-300">{{ tech.name }}</span>
          <div class="flex items-center gap-0.5 mt-1">
            <span v-for="i in 10" :key="i" class="flex flex-1 h-2 rounded-md"
              :class="i <= tech.level ? 'bg-green-700' : 'bg-gray-900'"></span>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: "TechStackSection",
  data() {
    return {
      frontendTechs: [
        { name: "Vue", level: 8 },
        { name: "TypeScript", level: 3 },
        { name: "React", level: 3 },
      ],
      sqlTechs: [
        { name: "Oracle", level: 7 },
        { name: "MySQL", level: 5 },
        { name: "Postgres", level: 3 },
      ],
      backendTechs: [
        { name: "Java", level: 7 },
        { name: "Node.js", level: 3 },
        { name: "PHP", level: 3 },
      ],
    };
  },
};
</script>
