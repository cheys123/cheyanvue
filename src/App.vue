<script setup>
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Education from './components/Education.vue'
import Experience from './components/Experience.vue'
</script>

<template>
  <div class="resume-container">
    <header class="header">
      <h1 class="title">My Resume</h1>
      <p class="contact">📧 cheyanbynygel2801@gmail.com | 📍 San Fernando, Pampanga</p>
    </header>

    <main>
      <About />
      <Skills />
      <Education />
      <Experience />
    </main>
  </div>
</template>

<style scoped>
/* Container */
.resume-container {
  max-width: 900px;
  margin: auto;
  padding: 2rem;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #333;
  line-height: 1.6;
  background: #fafafa;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

/* Header */
.header {
  text-align: center;
  margin-bottom: 2.5rem;
}

.title {
  font-size: 2.8rem;
  margin-bottom: 0.5rem;
  color: #2ecc71;
  font-weight: bold;
  letter-spacing: 1px;
}

.contact {
  font-size: 1rem;
  color: #555;
  font-style: italic;
}

/* Sections */
section {
  margin-bottom: 2rem;
  padding: 1.5rem;
  background: #fff;
  border-left: 5px solid #2ecc71;
  border-radius: 8px;
  transition: transform 0.2s ease-in-out;
}

section:hover {
  transform: translateX(5px);
}

h2 {
  font-size: 1.5rem;
  color: #2ecc71;
  margin-bottom: 0.8rem;
  border-bottom: 2px solid #eee;
  padding-bottom: 0.3rem;
}

p, li {
  font-size: 1rem;
  color: #444;
}

/* List styling */
ul {
  padding-left: 1.2rem;
}

li {
  margin-bottom: 0.5rem;
}
</style>
