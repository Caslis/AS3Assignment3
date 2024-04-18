<script setup lang="ts">
import Amirul from "./assets/Amirul.jpg";
</script>

<template>
  <main class="py-6 px-4 sm:p-6 md:py-10 md:px-8">
    <div class="max-w-4xl mx-auto grid grid-cols-1 lg:max-w-5xl lg:grid-cols-2">
      <div class="grid gap-4 col-start-1 col-end-3 row-start-1 sm:mb-6 sm:grid-cols-4 lg:gap-6 lg:col-start-2 lg:row-end-6 lg:row-span-6 lg:mb-0 relative">
        <img :src="Amirul" alt="Student Image" />
      </div>
      <div class="relative p-3 col-start-1 row-start-1 flex flex-col-reverse rounded-lg bg-gradient-to-t from-black/75 via-black/0 sm:bg-none sm:row-start-2 sm:p-0 lg:row-start-1">
        <div class="div-title mt-1 text-lg font-semibold text-white sm:text-slate-900 md:text-2xl dark:sm:text-white">
          Mirul's Profile 😎
        </div>
      </div>
      <div class="text-box">
        <p class="mt-4 text-sm leading-6 col-start-1 sm:col-span-2 lg:mt-6 lg:row-start-4 lg:col-span-1 dark:text-slate-400">
          My name is Mohammad Amirul Syafie, and I am a student at Politeknik Brunei, specializing in Web Development. Outside of academics, I enjoy playing games, particularly Valorant. I have a keen interest in continuous learning and am always eager to gain new experiences.
        </p>
      </div>    
    </div>
  </main>
</template>

<style scoped>
.text-box {
  border: 1px solid #ccc;
  padding: 10px;
  background-color: rgb(87, 83, 78);
}

.div-title {
  font-size: 2em;
  font-weight: bold;
}

@media (min-width: 1024px) {
  .grid {
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }

  .text-box {
    grid-column: 1 / span 2;
  }
}
</style>