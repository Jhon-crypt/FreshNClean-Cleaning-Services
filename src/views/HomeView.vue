<script setup>
import Header from '../components/header/header.vue'
import HeadingHero from '../components/hero/HeadingHero.vue'
import FeaturesSection from '../components/section/FeaturesSection.vue'
import SecondFeatures from '../components/section/SecondFeatures.vue'
import ThirdFeaturesSection from '../components/section/ThirdFeaturesSection.vue'
import GallerySection from '../components/section/GallerySection.vue'
import ContactSection from '../components/section/contactSection.vue'
import Footer from '../components/footer/Footer.vue'
</script>

<template>
  <main>
    <Header />
    <main class="px-2">
      <HeadingHero />
      <FeaturesSection />
      <SecondFeatures />
      <ThirdFeaturesSection />
      <GallerySection />
      <ContactSection />
    </main>
    <Footer />
  </main>
</template>
