<script setup lang="ts">
import Card from '~/components/Card.vue';

</script>

<template>
  <div class="w-dvw max-w-full h-[90dvh] flex justify-center items-center">
    <h1 class="text-4xl md:text-6xl mb-32">
      <span class="font-important">Recicle</span> sua <span class="text-primary">luz.</span>
    </h1>
  </div>

  <div id="presentation">
    <h2 class="text-4xl text-center mt-28">O que é?</h2>

    <div class="flex flex-wrap sm:justify-around justify-center gap-2">
      <p class="text-justify text-gray-600 text-sm mt-16 mb-8 w-64 md:w-96 px-4 md:px-0">
        Nosso projeto consiste numa luminária economicamente acessível e movida a energia solar.
        Sua carga é feita por meio de uma placa solar embutida, podendo ser carregada durante
        o dia e utilizada durante a noite, por exemplo. Com isso, tem-se uma forma democrática
        de propagar formas limpas de energia para aqueles que não possuem aparato solar completo
        em sua residência.
      </p>

      <div class="flex flex-wrap items-center justify-center">
        <NuxtImg 
          src="https://www.sgdes.pr.gov.br/sites/sgdes/arquivos_restritos/files/imagem/2024-06/07_0.png" 
          :width="90"
          :height="90"
        />

        <NuxtImg 
          src="https://www.sgdes.pr.gov.br/sites/sgdes/arquivos_restritos/files/imagem/2024-06/11_0.png" 
          :width="90"
          :height="90"
        />

        <NuxtImg 
          src="https://www.sgdes.pr.gov.br/sites/sgdes/arquivos_restritos/files/imagem/2024-06/12_0.png" 
          :width="90"
          :height="90"
        />

        <NuxtImg 
          src="https://www.sgdes.pr.gov.br/sites/sgdes/arquivos_restritos/files/imagem/2024-06/13_0.png" 
          :width="90"
          :height="90"
        />
      </div>
    </div>
  </div>

  <h2 class="text-4xl text-center mt-28" id="team">Quem somos?</h2>

  <div class="flex justify-center w-full">
    <p class="text-justify text-gray-600 text-sm mt-16 mb-8 w-64 md:w-96 px-4 md:px-0">Nossa equipe é integralmente formada por docentes e discentes
      do Ensino Médio do colégio ludovicense Upaon-Açu. Aqui, há integração entre jovens e profissionais
      para garantir um futuro melhor tanto para educação, quanto para a tecnologia, por meio do
      presente projeto.
    </p>
  </div>
  <div class="flex flex-wrap gap-3 mt-9 justify-center px-12">
    <Card
      title="Organizadores"
      :items="['Prof. Tássio', '´Prof Marconi Maia']"
    />
    <div class="w-full"></div>

    <Card 
      title="Desenvolvedores do website"
      :items="['André Jordão', 'Arthur Vieira', 'João Vitor Prazeres', 'Lucas Raposo', 'Thales Gabriel', 'Gustavo Moreira']"
    /> 

    <Card 
      title="Design/Marketing" 
      :items="['Maria Eduarda Porta', 'Vitória Roberta', 'Beatriz Evangelista', 'César Cauan',
        'Leandro Luís', 'Antônio Luís', 'Daniel Marinho', 'Pedro Arthur Pontes', 'Cristian Manuel',
        'Miguel Esteves', 'Neilton Júnior', 'Caio Vitor', 'Maria Araújo', 'Jorge Luís']" 
    />

    <Card
      title="Making of"
      :items="['Lucas Costa', 'Pedro Lucas', 'Arthur Morais', 'Anthony Araújo', 'Thiago José',
        'Max Filho', 'Sara Fernandes', 'Mateus Leone']"
    />

    <Card
      title="Podcast"
      :items="['Gabriela Sens', 'Maria Alice', 'Isadora Fernandes', 'Giovana Fook', 'Isaque Ryan',
        'Ângelo Pietro', 'Agata Aranha', 'Kayky Evangelista', 'Layla Sophia', 'Aline de Jesus',
        'Catharina Aroso'
      ]"
    />
  </div>

  <h2 class="text-4xl text-center mt-28" id="podcast">Nosso podcast</h2>
  <div class="flex mt-24 justify-center flex-wrap px-12 gap-3">
    <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/episode/49DqRvU6pYxyzBj4NCMnVn" width="352" height="152" frameBorder="0" allowfullscreen="false" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/episode/5lVPeSqBiupoTb97bUIBSr?si=clsiIpFJTVuK5L0WX_X-yw" width="352" height="152" frameBorder="0" allowfullscreen="false" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    <iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/episode/7cikKzyBuacoEhkmorfdI2?si=0cf823e1e262454f" width="100%" height="352" frameBorder="0" allowfullscreen="false" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
  </div>
</template>
