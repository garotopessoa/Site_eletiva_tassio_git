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
  <div class="flex mt-24 justify-center flex-wrap sm:px-12 gap-3 mb-24">
    <Episode url="https://open.spotify.com/embed/episode/1oVUtuO63EQ5ymmtisjqqn" />
    <Episode url="https://open.spotify.com/embed/episode/0TAjaXNMbYFSTWTZ6oviZp?si=6f42b468ff2f4cc4" />
    <Episode url="https://open.spotify.com/embed/episode/5Vp4mejsnaFu54W2d55NiO?si=23dc100036fd4525" />
    <Episode url="https://open.spotify.com/embed/episode/0P8lYr54eZm6bmf1wakbdO?si=18d7565cb1cf4e51" />
    <Episode url="https://open.spotify.com/embed/episode/0EOkgIj1tJFpSvXW8RNosZ?si=9ee73c360ce9471b" />
    <Episode url="https://open.spotify.com/embed/episode/4JmjkLXjNF6jN1GkAMq389?si=22950c97f7c541d1" />
    <Episode url="https://open.spotify.com/embed/episode/55jIshlfSbLKtDqq0zfBSs?si=da7d730b44ed4984" />
    <Episode url="https://open.spotify.com/embed/episode/5RHs016oN1PyL8qRvOYPHH?si=264b70bd960b4005" />
    <Episode url="https://open.spotify.com/embed/episode/0kGk31IUcvTNIiJND6VbWI?si=90a4b523054b4d20" />
    <Episode url="https://open.spotify.com/embed/episode/0aULEBZGkjQyffdlRsCqpF?si=271577376fd849c5" />
  </div>
</template>
