<template>
  <div 
    class="w-full flex justify-center bg-neutral-900 h-screen text-orange-50"
  >
    <main class="w-full overflow-auto">
      <navbar />
      <div class="flex justify-center mt-10">
        <slot />
      </div>
    </main>
  </div>

</template>

<script setup >
</script>

<style scoped>

</style>
