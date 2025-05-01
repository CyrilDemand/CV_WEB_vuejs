<script setup>
import TextLink from './TextLink.vue'
</script>

<template>
  <section id="about">
    <p class="mb-4">I'm a developer passionate about making robust and useful application.</p>

    <p class="mb-4">
      Currently I'm an apprentice software engineer working at
      <TextLink label="Worldline" link="https://worldline.com" />
      for
      <TextLink label="France Titres" link="https://ants.gouv.fr/" />
      which is a part of the french governement. Beside it I'm studying at
      <TextLink label="IMT Nord Europe" link="https://imt-nord-europe.fr/" />
      I contribute to the creation and maintenance of web applications that helps the gouvernement
      to manage National Identity Card, Passport, Residence Permit Card, Driver licenses, 2D-Doc.
    </p>

    <p>
      In the past, I've had the opportunity to develop software across a variety of settings — from
      <TextLink
        label="the army ministery"
        link="https://www.defense.gouv.fr/ema/etablissement-geographique-interarmees-egi"
      />
      <TextLink label="the interior ministery" link="https://ants.gouv.fr/" />
      and
      <TextLink label="large corporations" link="https://www.tvh.com/fr-fr" />. Additionally, I also
      did several group projects for my schools and did game james with friends.
    </p>

    <p>
      In my spare time, I'm usually running, going to the gym, reading, playing video games,
      watching series or hanging out with my friends. And playing piano when I find some courage and
      time. I'm currently playing
      <TextLink
        label="Clair Obscur Expedition 33"
        link="https://fr.bandainamcoent.eu/clair-obscur/clair-obscur-expedition-33"
      />
    </p>
  </section>
</template>
