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
        "MongoDB", "Git & GitHub", "SQL", "AWS", "Java", "Python", "PHP"
      ]
    };
  }
};
</script>

<style scoped>
.skills ul {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  padding: 10px 0;
}

.skills li {
  background-color: #e0f7fa;
  padding: 8px 12px;
  border-radius: 20px;
  color: #00796b;
  font-weight: 500;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
</style>
