<template>
    <div class="bg-[#111827] min-h-screen">
      <NavBar />
      <HeroSection />
      <ServicesSection/>
      <AboutSection/>
      <Experiencesandskills/>
      <LatestProjects/>
      <ContactSection/>
      <FooterSection/>
      <BackToTopFunction/>
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
  const ContactSection=defineAsyncComponent(()=> import('@/components/ContactSection.vue'));
  const TestimonialsSection=defineAsyncComponent(()=> import('@/components/TestimonialsSection.vue'));
  const FooterSection=defineAsyncComponent(()=> import('@/components/FooterSection.vue'));
  const BackToTopFunction=defineAsyncComponent(()=> import('@/components/BackToTopFunction.vue'));
  const LoadingSpinnerFunction = defineAsyncComponent(()=> import('@/components/LoadingSpinnerFunction.vue'));

  </script>
  