<template>
  <div class="w-dvw max-w-full h-[90dvh] flex justify-center items-center">
    <h1 class="text-4xl md:text-6xl mb-32">
      <span class="font-important">Recicle</span> sua <span class="text-primary">luz.</span>
    </h1>
  </div>

  <h2 class="text-4xl text-center mt-28" id="team">Quem somos?</h2>
  <div class="flex flex-wrap gap-3 mt-9 justify-center px-12">
    <UCard variant="soft">
      <template #header>
        Arthur Vieira
      </template>

      <template #footer>
        Lorem ipsum dolor sit amet
        <UAvatar src="https://github.com/arthurdeveloper.png" />
      </template>
    </UCard>

    <UCard variant="soft">
      <template #header>
        Lucas Raposo
      </template>

      <template #footer>
        Lorem ipsum dolor sit amet
        <UAvatar src="https://github.com/garotopessoa.png" />
      </template>
    </UCard>

    <UCard variant="soft">
      <template #header>
        Equipe
      </template>

      <template #footer>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        Morbi suscipit sapien augue, dapibus auctor metus luctus vel.
        Pellentesque non risus id orci ornare consectetur sit amet dignissim velit.
        Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
        Nunc posuere lacus enim, in aliquam orci sodales nec.
        Donec pellentesque purus purus, id placerat turpis fringilla nec.
        Pellentesque lacinia arcu non venenatis iaculis. Fusce ut varius sem.
        <UAvatar src="https://github.com/arthurdeveloper.png" />
      </template>
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
