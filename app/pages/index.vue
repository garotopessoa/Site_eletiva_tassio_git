<template>
  <div class="w-dvw max-w-full h-[90dvh] flex justify-center items-center">
    <h1 class="text-4xl md:text-6xl mb-32">
      <span class="font-important">Recicle</span> sua <span class="text-primary">luz.</span>
    </h1>
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
    <UCard variant="soft">
      <template #header>
        <div class="ml-3">Organizador</div>
      </template>

      <List :items="['Prof. Tássio']" />
    </UCard>
    <div class="w-full"></div>

    <UCard variant="soft">
      <template #header>
        Desenvolvedores do website
      </template>

      <List :items="['André Jordão', 'Arthur Vieira', 'João Vitor Prazeres', 'Lucas Raposo']" />
    </UCard>

    <UCard variant="soft">
      <template #header>
        Design/Marketing
      </template>

      <List :items="['Maria Eduarda Porta', 'Vitória Roberta', 'Beatriz Evangelista', 'César Cauan',
        'Leandro Luís', 'Antônio Luís', 'Daniel Marinho', 'Pedro Arthur Pontes', 'Cristian Manuel',
        'Miguel Esteves', 'Neilton Júnior', 'Caio Vitor'
      ]" />
    </UCard>

    <UCard variant="soft">
      <template #header>
        Making off
      </template>

      <List :items="['Lucas Costa', 'Pedro Lucas', 'Arthur Morais', 'Anthony Araújo', 'Thiago José',
        'Max Filho', 'Sara'
      ]" />
    </UCard>

    <UCard variant="soft">
      <template #header>
        Podcast
      </template>

      <List :items="['Gabriela Sena', 'Maria Aule', 'Isadora Fernandes', 'Giovana Fook', 'Isaque Ryan',
        'Ângelo Pietro', 'Agata Aranha', 'Kayky Evangelista', 'Layla Sophia', 'Aline de Jesus'
      ]" />
    </UCard>


  </div>

  <h2 class="text-4xl text-center mt-28" id="podcast">Nosso podcast</h2>
  <div class="flex mt-9 justify-center flex-wrap px-12 gap-3">
    <UCard variant="soft">
      <template #header>
        Exemplo
      </template>

      <iframe
        height="315"
        src="https://www.youtube.com/embed/_CSjq-UyaWA"
        title="Secos &amp; Molhados - Sangue Latino [Raridade]"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen
        style="width: 100%; aspect-ratio: 16 / 9; height:315px;"
      />

      <template #footer>
        Episódio de exemplo
      </template>
    </UCard>

    <UCard variant="soft">
      <template #header>
        Exemplo
      </template>

      <iframe 
        width="560"
        height="315"
        src="https://www.youtube.com/embed/CNovnrkM8XU"
        title="Travessia | Milton Nascimento"
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" 
        allowfullscreen
        style="width: 100%; aspect-ratio: 16 / 9; height:315px;">
      </iframe>

      <template #footer>
        Episódio de exemplo
      </template>
    </UCard>

    <UCard variant="soft">
      <template #header>
        Exemplo
      </template>

      <iframe 
        width="560" 
        height="315" 
        src="https://www.youtube.com/embed/i53ndlSMqSs" 
        title="Gal Costa e Tim Maia - Um dia de domingo (Fantástico) [Raridade]" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
        referrerpolicy="strict-origin-when-cross-origin" 
        allowfullscreen
        style="width: 100%; aspect-ratio: 16 / 9; height:315px;">
      </iframe>
      <template #footer>
        Episódio de exemplo
      </template>
    </UCard>

    <UCard variant="soft">
      <template #header>
        Exemplo
      </template>

      <iframe 
        width="525" 
        height="394" 
        src="https://www.youtube.com/embed/958mJ3rV_LQ" 
        title="The Beatles - Twist &amp; Shout (Live At The Royal Variety Performance)" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
        referrerpolicy="strict-origin-when-cross-origin" 
        allowfullscreen
        style="width: 100%; aspect-ratio: 16 / 9; height:315px;">
      </iframe>
      <template #footer>
        Episódio de exemplo
      </template>
    </UCard>
  </div>
</template>
