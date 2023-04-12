<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<div class="max-w-md mx-auto bg-zinc-300 rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:shrink-0">
      <img class="h-48 w-full object-cover md:h-full md:w-48" src="/src/assets/studentimage/HAMIMI_SICT_PHOTO.jpg" alt="MIMI">
    </div>
    <div class="p-8">
      <div class="uppercase tracking-wide text-sm text-pink-500 font-semibold">Nur Hamimi Binti Haji Rashid</div>
      <a href="https://pb.edu.bn/" class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Politeknik Brunei</a>
      <p class="mt-2 text-gray-900">Diploma in Web Development</p>

      <br>
      
      <a href=mailto:“21FTT1286@student.pb.edu.bn” class="text-gray-200 block rounded-lg text-center font-medium leading-6 px-6 py-3 bg-pink-500 hover:bg-black hover:text-white"><span class="font-bold">21FTT1286@student.pb.edu.bn</span></a>

    </div>  
  </div>
</div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>




