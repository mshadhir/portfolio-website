<template>
    <div class="app">
      <HeaderSection />
      <AboutSection />
      <SkillsSection />
      <ExperienceSection />
      <CertificationsSection />
      <ProjectsSection />
      <ContactSection />
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
  