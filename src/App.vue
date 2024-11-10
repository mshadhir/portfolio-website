<template>
  <div class="app">
    <HeaderSection />
    <section id="about"><AboutSection /></section>
    <section id="skills"><SkillsSection /></section>
    <section id="projects"><ProjectsSection /></section>
    <section id="contact"><ContactSection /></section>
  </div>
</template>

  
  <script>
  import HeaderSection from './components/HeaderSection.vue';
  import AboutSection from './components/AboutSection.vue';
  import SkillsSection from './components/SkillsSection.vue';
  import ExperienceSection from './components/ExperienceSection.vue';
  import CertificationsSection from './components/CertificationsSection.vue';
  import ProjectsSection from './components/ProjectsSection.vue';
  import ContactSection from './components/ContactSection.vue';
  
  export default {
    components: {
      HeaderSection,
      AboutSection,
      SkillsSection,
      ExperienceSection,
      CertificationsSection,
      ProjectsSection,
      ContactSection
    }
  };
  </script>
  