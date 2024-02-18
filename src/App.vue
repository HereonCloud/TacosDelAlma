<script setup lang="ts">
import HeroSection from './components/HeroSection.vue'
import IntroSection from './components/IntroSection.vue'
import GallerySection from './components/GallerySection.vue'
import DescriptionSection from './components/DescriptionSection.vue'
const descriptionText1 =
  'The vibrant "Salsa Red" is the heartbeat of Tacos del Alma\'s color palette. This energetic and passionate red reflects the bold flavors and spices that define our tacos. "Corn Gold" adds a warm and comforting touch to the color scheme, paying homage to the essential ingredient in our tacos—the corn tortilla. '

const descriptionText2 =
  'The neutral "Beige Earth" serves as a grounding element in Tacos del Alma\'s color palette. This earthy tone represents the wholesome and natural aspects of our ingredients.'
</script>

<template>
  <HeroSection></HeroSection>
  <IntroSection></IntroSection>
  <GallerySection></GallerySection>
  <DescriptionSection
    :description1="descriptionText1"
    :description2="descriptionText2"
    direction="right"
  ></DescriptionSection>
</template>

<style scoped></style>
