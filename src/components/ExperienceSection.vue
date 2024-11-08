<template>
    <section class="experience">
      <h2>Experience</h2>
      <div v-for="job in jobs" :key="job.title" class="job">
        <h3>{{ job.title }} - {{ job.company }}</h3>
        <p><em>{{ job.dates }}</em></p>
        <ul>
          <li v-for="responsibility in job.responsibilities" :key="responsibility">{{ responsibility }}</li>
        </ul>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'ExperienceSection',
    data() {
      return {
        jobs: [
          {
            title: "Supervisor Dispatch Operations",
            company: "Woolworths Group",
            dates: "Aug 2024 - Present",
            responsibilities: [
              "Spearheaded dispatch operations, ensuring seamless order processing and on-time delivery.",
              "Optimized inventory management with data-driven practices.",
              "Led continuous improvement initiatives utilizing Lean methodologies."
            ]
          },
          {
            title: "Customer Service Executive",
            company: "HSBC",
            dates: "May 2021 - Nov 2022",
            responsibilities: [
              "Developed customer service policies to enhance customer experience.",
              "Analyzed customer feedback and improved service processes.",
              "Managed and mentored a team, improving team performance."
            ]
          }
        ]
      };
    }
  };
  </script>
  
  <style scoped>
  .job {
    margin-bottom: 20px;
  }
  </style>
  