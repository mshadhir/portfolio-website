<template>
    <section class="certifications">
      <h2>Certifications</h2>
      <ul>
        <li v-for="certification in certifications" :key="certification.name">
          <strong>{{ certification.name }}</strong> - {{ certification.issuer }} ({{ certification.date }})
        </li>
      </ul>
    </section>
  </template>
  
  <script>
  export default {
    name: 'CertificationsSection',
    data() {
      return {
        certifications: [
          { name: "Programming Foundations: Object-Oriented Design", issuer: "LinkedIn Learning", date: "Feb 2024" },
          { name: "Four Simple Strategies to Boost Creativity and Productivity", issuer: "LinkedIn Learning", date: "Jan 2024" },
          { name: "Python for Beginners", issuer: "University of Moratuwa", date: "May 2022" },
          { name: "Java Advanced Certification Course", issuer: "Programming Hub", date: "Apr 2020" }
        ]
      };
    }
  };
  </script>
  