<template>
  <header class="header">
    <h1>Shadhir Jaibulla</h1>
    <p class="subtitle">IT Undergraduate</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#experience">Experience</a>
      <a href="#certifications">Certifications</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderSection'
};
</script>

<style scoped>
.header {
  text-align: center;
  padding: 30px;
  background: #4A90E2;
  color: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
  margin-bottom: 40px;
  transition: transform 0.3s ease;
}

.header:hover {
  transform: scale(1.02);
}

.header h1 {
  font-size: 2.8rem;
  font-weight: 700;
  letter-spacing: 1px;
  margin-bottom: 5px;
}

.subtitle {
  font-size: 1.2rem;
  font-weight: 400;
  color: #f9a826;
}

nav {
  margin-top: 10px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
  font-size: 1.1rem;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #f9a826;
}
</style>
