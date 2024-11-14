<template>
  <section class="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:mshadhir3@gmail.com">mshadhir3@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/shadhir" target="_blank" rel="noopener noreferrer">Shadhir Jaibulla</a></p>
    <a href="/src/assets/resume.pdf" download class="resume-button">Download Resume</a>

  </section>
</template>

<script>
export default {
  name: 'ContactSection'
};
</script>

<style scoped>
.contact {
  text-align: center;
}

.resume-button {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  color: #4A90E2;
  background-color: #fff;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
  transition: background-color 0.3s, color 0.3s;
}

.resume-button:hover {
  background-color: #f9a826;
  color: #fff;
}
</style>
