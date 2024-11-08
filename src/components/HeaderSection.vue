<template>
  <header class="header">
    <h1>Shadhir Jaibulla</h1>
    <nav>
      <a href="#about">About</a> |
      <a href="#skills">Skills</a> |
      <a href="#projects">Projects</a> |
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
  padding: 20px;
  background-color: #4A90E2;
  color: #fff;
  border-radius: 8px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 10px;
}

nav a:hover {
  text-decoration: underline;
}
</style>
