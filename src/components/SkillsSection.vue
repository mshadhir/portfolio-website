<template>
    <section class="skills">
      <h2>Skills</h2>
      <ul>
        <li v-for="skill in skills" :key="skill">{{ skill }}</li>
      </ul>
    </section>
  </template>
  
  <script>
  export default {
    name: 'SkillsSection',
    data() {
      return {
        skills: [
          "JavaScript", "Vue.js", "HTML & CSS", "Node.js",
          "MongoDB", "Git & GitHub", "SQL", "AWS Basics"
        ]
      };
    }
  };
  </script>
  
  <style scoped>
  .skills ul {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }
  
  .skills li {
    background-color: #e8f4fa;
    padding: 5px 10px;
    border-radius: 5px;
    color: #333;
  }
  </style>

