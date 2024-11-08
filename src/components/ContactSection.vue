<template>
  <section class="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:mshadhir3@gmail.com">mshadhir3@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/shadhir" target="_blank" rel="noopener noreferrer">Shadhir Jaibulla</a></p>
    <div class="social-links">
      <a href="https://www.linkedin.com/in/shadhir" target="_blank" rel="noopener noreferrer"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/mshadhir" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a>
      <!-- Add other social media icons as needed -->
    </div>
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

.contact a {
  color: #4A90E2;
}

.contact a:hover {
  text-decoration: underline;
}
</style>
