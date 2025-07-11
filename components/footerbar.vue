<template>
  <footer class="py-6">
    <div class="container mx-auto px-4 flex flex-col md:flex-row justify-between items-center gap-4 w-1/3">
      <p class="text-sm text-center md:text-left">&copy; {{ year }} Akin Fantuci. Todos os direitos reservados.</p>

      <div class="flex space-x-4">
        <a href="https://github.com/akinj15" target="_blank">
          <Icon name="mdi:github" class="w-11" size="24px"/>
        </a>
        <a href="https://www.linkedin.com/in/akin-fantuci-7b2234207/" target="_blank">
          <Icon name="mdi:linkedin" class="" size="24px"/>
        </a>
      </div>
    </div>
  </footer>

</template>

<script setup>

</script>

<style scoped>
.main {
  max-width: 768px;
}
</style>
