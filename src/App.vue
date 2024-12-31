<template>
    <div class="bg-[#111827] min-h-screen">
      <NavBar />
      <HeroSection />
      <ServicesSection/>
      <AboutSection/>
      <Experiencesandskills/>
      <LatestProjects/>
    </div>
  </template>
  
  <script setup>
  import { defineAsyncComponent } from 'vue';
  // Import Components Asynchronously
  const NavBar = defineAsyncComponent(() => import('@/components/NavBar.vue'));
  const HeroSection = defineAsyncComponent(() => import('@/components/HeroSection.vue'));
  const ServicesSection = defineAsyncComponent(() => import('@/components/ServicesSection.vue'));
  const AboutSection = defineAsyncComponent(() => import('@/components/AboutSection.vue'));
  const Experiencesandskills=defineAsyncComponent(()=> import('@/components/Experience&skills.vue'));
  const LatestProjects=defineAsyncComponent(()=> import('@/components/LatestProjectsSection.vue'));
  </script>
  