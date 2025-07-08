<template>
  <footer class="py-6">
    <div class="container mx-auto px-4 flex flex-col md:flex-row justify-between items-center gap-4 w-1/3">
      <p class="text-sm text-center md:text-left">&copy; {{ year }} Minha Empresa. Todos os direitos reservados.</p>

      <div class="flex space-x-4">
        <a href="#" class="hover:underline">Privacidade</a>
        <a href="#" class="hover:underline">Termos</a>
        <a href="#" class="hover:underline">Contato</a>
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
