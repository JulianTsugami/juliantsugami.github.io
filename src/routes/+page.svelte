<script lang="ts">
  import Header from '../components/Header.svelte';
  import About from '../components/About.svelte';
  import Skills from '../components/Skills.svelte';
  import Experience from '../components/Experience.svelte';
  import Projects from '../components/Projects.svelte';
  import Footer from '../components/Footer.svelte';
</script>

<Header />
<main class="container">
  <About />
  <hr />
  <Skills />
  <hr />
  <Experience />
  <hr />
  <Projects />
</main>

<Footer />
