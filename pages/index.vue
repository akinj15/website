<template>
  <div class="w-full max-w-xl p-4">

    <div class="md:flex md:justify-between ">
      <div class=" mt-4">
          <h2 class="text-4xl">
            Akin Fantuci
          </h2>
          <p>
            Programador Full-stack ( Nodejs / Golang )
          </p>
      </div>
      <div class="mt-4">
        <div class="" >
          <img class="rounded-full mx-auto" src="../public/perfil.jpeg" alt="foto de perfil pessoal" width="90">
        </div>
      </div>
    </div>
    <div class="overflow-hidden">
      <DoonFire></DoonFire>
    </div>
    <div class="text-center rounded-b-lg p-4 w-full bg-fire text-neutral-900"> 
      <p>Desenvolvedor Full-stack</p>
    </div>
    <div class="my-4">
      <div class=" my-4">
          <h4 class="inline-block text-2xl border-b-4 border-neutral-700 my-4">
            Eu
          </h4>
          <p>
            Sou programador Full-stack focado em Javascript, ja trabalhei em varios projetos React, Vue, Angular, Nest, Next, Nuxt, Express, Golang com experencia em desenvolvimento de sistemas ERP, CRM, Ponto de Venda(PDV) e aplicações web.  
            <br> 
            Atualmente trabalho como Desenvolvedor na Innovaro, comecei na área de programação em 2021 como Estagiário, além de atuar como voluntário internacional em projetos multiculturais. 
          </p>
      </div>
    </div>
    <div class="my-4">
      <div class=" my-2">
          <h4 class="inline-block text-2xl border-b-4 border-neutral-700 my-4">
            Trabalho
          </h4>
          <p class="my-3">
            <Timestamp>2022 - October to present</Timestamp> 
              Desenvolvedor de sistemas ERP, Integrações, Pontos de Vendas, na Innovaro.
          </p>
          <p class="my-3">
            <Timestamp>2023 - May to 2023 - August</Timestamp> 
              Estagiário Voluntario internacional como desenvolvedor FrontEnd React na empresa Eternal Technology.
              Atuando no desenvolvimento da plataforma de ensino codei.pro como Front End - Reactjs / Typescript. 
          </p>
          <p class="my-3">
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
              React, Next, Vue.js 2/3, Quasar, Angular, Nodejs, Nest.js, Express, SQL, MongoDb, Postgres, Firebase, Python, Go, Linux ... 
            </Batch>
          </p>
                    <h4 class="inline-block text-2xl border-b-4 border-neutral-700 my-4">
            Linguagens
          </h4>
          <p class="my-2">
            <Batch>
              Javascript, Typescript, Golang, Python, Lua ... 
            </Batch>
          </p>

      </div>
    </div>
  </div>
</template>
<script setup>
</script>


<style scoped>
.bg-fire {
  background-color: rgb(239, 239, 199);
}
</style>
