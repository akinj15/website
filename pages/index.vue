<template>
  <div class="w-full max-w-xl p-4">

    <div class="md:flex md:justify-between ">
      <div class=" mt-4">
          <h2 class="text-4xl">
            Akin Fantuci
          </h2>
          <p>
            Programador Full-stack ( Vue.js / Nodejs )
          </p>
      </div>
      <div class="mt-4">
        <div class="" >
          <img class="rounded-full mx-auto border-2" src="../public/cat.jpg" alt="foto de perfil pessoal" width="90" height="100">
        </div>
      </div>
    </div>
    <div class="overflow-hidden">
      <DoonFire></DoonFire>
    </div>
    <div class="text-center rounded-b-lg p-4 w-full bg-fire text-neutral-900"> 
      <p>Desenvolvedor Full-stack Vue.js e nodejs baseado no odio</p>
    </div>
    <div class="my-4">
      <div class=" my-4">
          <h4 class="inline-block text-2xl border-b-4 border-neutral-700 my-4">
            Eu
          </h4>
          <p>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            Atualmente trabalho na innovaro, uma empresa cria soluções empresariais e gestão. Sou um programador 
            Full-stack focado em Vue.js e Node.js, ja trabalhei em varios projetos web criando desde um aplicação para gestão de academias
            á aplicações de gestão de vendedores. E sigo fazendo alguns freelancers no meu tempo livre.
          </p>
      </div>
    </div>
    <div class="my-4">
      <div class=" my-2">
          <h4 class="inline-block text-2xl border-b-4 border-neutral-700 my-4">
            Trabalho
          </h4>
          <p class="my-2">
            <Timestamp>2022 - October to present</Timestamp> 
              Desenvolvedor de sistemas ERP usando framework ENGINE desenvolvendo soluções empresariais, na Innovaro.
          </p>
          <p class="my-2">
            <Timestamp>2021 - October to 2022 - October</Timestamp> Estágio como Desenvolvedor Front-end, na HR fabrica de software.
          </p>
      </div>
    </div>
    <div class="my-4">
      <div class=" my-2">
          <h4 class="inline-block text-2xl border-b-4 border-neutral-700 my-4">
            Escolaridade
          </h4>
          <p class="my-2">
            <Timestamp>2021 - Jan to 2023 - Jan</Timestamp> 
              Cursou - Analises e desenvolvimento de sistemas.
          </p>
      </div>
    </div>
    <div class="my-4">
      <div class=" my-2">
          <h4 class="inline-block text-2xl border-b-4 border-neutral-700 my-4">
            Tecnologias
          </h4>
          <p class="my-2">
            <Batch>
              Vue.js 2/3, Quasar, Nodejs, Nest.js, SQL, MongoDb, Python, Go, Linux ... 
            </Batch>
          </p>
      </div>
    </div>
    <p>Content inside <code>default</code> layout</p>
  </div>
</template>
<script setup>
</script>


<style scoped>
.bg-fire {
  background-color: rgb(239, 239, 199);
}
</style>
