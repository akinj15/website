<template>
  <nav class="w-full bg-neutral-900/50 p-lg fixed z-10 backdrop-blur">
    <div class="flex itens-stretch justify-center main mx-auto">
      <div class="w-1/5 text-lg p-4">
        <nuxt-link 
          class="text-orange-100"
          to="/"
        >
          Akin
        </nuxt-link>
      </div>
      <div class="flex  items-center text-base w-4/5  p-4">
        <!-- <nuxt-link 
          class="px-4 hover:underline hover:underline-offset-4"
          to="/bio"
        >
          bio
        </nuxt-link> -->
        <nuxt-link 
          class="px-4 hover:underline hover:underline-offset-4 text-orange-100"
          to="/about"
        >
          about
        </nuxt-link>
        <a 
          class="flex items-center gap-1 px-4 hover:underline hover:underline-offset-4 text-orange-100"
          href="https://github.com/akinj15"
          target="_blank"
        >
          source
          <Icon name="mdi:github" class="" size="24px"/>
        </a>
      </div>
    </div>
  </nav>

</template>

<script setup>

</script>

<style scoped>
.main {
  max-width: 768px;
}
</style>
