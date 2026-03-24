<script setup>
  // Skriptni dio još ne učimo
</script>

<template>
  <div class="min-h-screen bg-gray-100 p-8 flex flex-col items-center">
    
    <h1 class="text-3xl font-bold text-gray-800 mb-8 text-center">
      Moja 3x3 Galerija
    </h1>

    <div class="grid !grid-cols-3 gap-4 w-full max-w-4xl justify-center items-center">
      
      <img src="https://picsum.photos/400?random=1" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 1">
      <img src="https://picsum.photos/400?random=2" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 2">
      <img src="https://picsum.photos/400?random=3" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 3">
      
      <img src="https://picsum.photos/400?random=4" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 4">
      <img src="https://picsum.photos/400?random=5" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 5">
      <img src="https://picsum.photos/400?random=6" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 6">
      
      <img src="https://picsum.photos/400?random=7" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 7">
      <img src="https://picsum.photos/400?random=8" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 8">
      <img src="https://picsum.photos/400?random=9" class="w-full min-w-0 aspect-square object-cover rounded-lg shadow-md" alt="Slika 9">
      
    </div>
  </div>
</template>

<style scoped>
/* Ako Tailwind grid-cols-3 i dalje zeza zbog neke vanjske postavke, 
   ovaj CSS će ga 100% natjerati na 3 stupca: */
.grid {
  display: grid !important;
  grid-template-columns: repeat(3, minmax(0, 1fr)) !important;
}
</style>