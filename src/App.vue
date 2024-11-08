<template>
    <div class="app">
        <HeaderSection />
        <AboutSection />
        <SkillsSection /> <!-- New Section -->
        <ProjectsSection />
        <ContactSection />
    </div>
  </template>
  
  <script>
  import HeaderSection from './components/HeaderSection.vue';
  import AboutSection from './components/AboutSection.vue';
  import SkillsSection from './components/SkillsSection.vue';
  import ProjectsSection from './components/ProjectsSection.vue';
  import ContactSection from './components/ContactSection.vue';
  
  export default {
      components: {
          HeaderSection,
          AboutSection,
          SkillsSection,
          ProjectsSection,
          ContactSection
      }
  };
  </script>
  
  <style src="./assets/styles.css"></style>
  