<template>
  <div class="app">
    <!-- Only include HeaderSection once at the top -->
    <HeaderSection />
    
    <!-- Main content sections -->
    <section id="about"><AboutSection /></section>
    <section id="skills"><SkillsSection /></section>
    <section id="projects"><ProjectsSection /></section>
    <section id="experience"><ExperienceSection /></section>
    <section id="certifications"><CertificationsSection /></section>
    <section id="contact"><ContactSection /></section>
  </div>
</template>

<script>
import HeaderSection from './components/HeaderSection.vue';
import AboutSection from './components/AboutSection.vue';
import SkillsSection from './components/SkillsSection.vue';
import ProjectsSection from './components/ProjectsSection.vue';
import ExperienceSection from './components/ExperienceSection.vue';
import CertificationsSection from './components/CertificationsSection.vue';
import ContactSection from './components/ContactSection.vue';

export default {
  components: {
    HeaderSection,
    AboutSection,
    SkillsSection,
    ProjectsSection,
    ExperienceSection,
    CertificationsSection,
    ContactSection
  }
};
</script>

<style src="./assets/styles.css"></style>
