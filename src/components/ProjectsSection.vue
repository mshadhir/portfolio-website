<template>
  <section class="projects">
    <h2>Projects</h2>
    <ul>
      <li v-for="project in projects" :key="project.title">
        <strong>{{ project.title }}:</strong> {{ project.description }}
        <div v-if="project.link">
          <a :href="project.link" target="_blank" rel="noopener noreferrer">View on GitHub</a>
        </div>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection',
  data() {
    return {
      projects: [
        {
          title: "Portfolio Website",
          description: "A personal portfolio website built with Vue.js, showcasing a modern, responsive UI with interactive elements and gradient backgrounds.",
          link: "https://github.com/mshadhir/portfolio-website"
        },
        {
          title: "Cybering Labs – IT Industry Project",
          description: "Contributed to Cyber Mind cybersecurity platform with new training labs.",
          link: "https://github.com/mshadhir/cybering-labs"
        },
        {
          title: "Swinburne Seed Library",
          description: "Created a Mendix app for users to explore, reserve, and rate seeds.",
          link: "https://github.com/mshadhir/swinburne-seed-library"
        },
        {
          title: "ICT Design Project - Gauntlet",
          description: "Enhanced UI for cybersecurity exercises on Retrospect Labs' platform."
        }
      ]
    };
  }
};
</script>
