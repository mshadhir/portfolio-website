<template>
  <section class="projects">
    <h2>Projects</h2>
    <div class="project-cards">
      <div v-for="project in projects" :key="project.title" class="project-card">
        <img :src="project.image" :alt="`Screenshot of ${project.title}`" class="project-image"/>
        <div class="project-details">
          <h3>{{ project.title }}</h3>
          <p>{{ project.description }}</p>
          <a :href="project.link" target="_blank" rel="noopener noreferrer">View on GitHub</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
// Import your images (add actual paths or replace with placeholder images)
import portfolioImage from '../assets/portfolio-website-preview.png';
import cyberingImage from '../assets/cybering-labs-preview.jpg';
import seedLibraryImage from '../assets/swinburne-seed-library-preview.jpg';
import gauntletImage from '../assets/ict-design-project-preview.jpg';
//import friendSystemImage from '../assets/friend-system-preview.png'; 
//import eventPlanningImage from '../assets/event-planning-preview.png'; 

export default {
  name: 'ProjectsSection',
  data() {
    return {
      projects: [
        {
          title: "Portfolio Website",
          description: "A personal portfolio website built with Vue.js, showcasing a modern, responsive UI with interactive elements and gradient backgrounds.",
          image: portfolioImage,
          link: "https://github.com/mshadhir/portfolio-website"
        },
        {
          title: "Cybering Labs – IT Industry Project",
          description: "Contributed to Cyber Mind cybersecurity platform with new training labs.",
          image: cyberingImage,
          link: "https://github.com/mshadhir/cybering-labs"
        },
        {
          title: "Swinburne Seed Library",
          description: "Created a Mendix app for users to explore, reserve, and rate seeds.",
          image: seedLibraryImage,
          link: "https://github.com/mshadhir/swinburne-seed-library"
        },
        {
          title: "ICT Design Project - Gauntlet",
          description: "Enhanced UI for cybersecurity exercises on Retrospect Labs' platform.",
          image: gauntletImage,
          link: "https://github.com/mshadhir/ict-design-project"
        },
        // New Projects
        {
          title: "My Friend System",
          description: "Developed a user-friendly web-based social networking app, with user registration, login, friend management, and database integration. I also added advanced features like pagination and mutual friend counts.",
          image: gauntletImage,
          link: "https://github.com/mshadhir/my-friend-system" 
        },
        {
          title: "Event Planning System",
          description: "Online Event Planning System is a web application that lets users manage their events (CRUD Operations).",
          image: gauntletImage,
          link: "https://github.com/mshadhir/event-planning-system" 
        },
      ]
    };
  }
};
</script>

<style scoped>
.project-cards {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.project-card {
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  width: 100%;
  max-width: 300px;
  transition: transform 0.3s, box-shadow 0.3s;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.project-image {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.project-details {
  padding: 15px;
}

.project-details h3 {
  font-size: 1.3rem;
  color: #333;
  margin-bottom: 8px;
}

.project-details p {
  color: #555;
  font-size: 1rem;
  margin-bottom: 12px;
}

.project-details a {
  color: #4A90E2;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s;
}

.project-details a:hover {
  color: #f9a826;
}
</style>
