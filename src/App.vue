<template>
  <div class="app">
      <HeaderSection />
      <AboutSection />
      <ProjectsSection />
      <ContactSection />
  </div>
</template>

<script>
import HeaderSection from './components/HeaderSection.vue';
import AboutSection from './components/AboutSection.vue';
import ProjectsSection from './components/ProjectsSection.vue';
import ContactSection from './components/ContactSection.vue';

export default {
    components: {
        HeaderSection,
        AboutSection,
        ProjectsSection,
        ContactSection
    }
};
</script>

<style src="./assets/styles.css"></style>
