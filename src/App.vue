<template>
  <div>
    <header>
    <NavBar />
  </header>
  <main>
    <HeroMain/>
    <AboutMain/>
    <SkillsMain/>
    <ProjectsMain/>
  </main>
  <FooterMain/>
  </div>
</template>

<script>
import NavBar from './components/Navbar.vue';
import HeroMain from './components/Hero.vue';
import AboutMain from './components/About.vue';
import FooterMain from './components/Footer.vue';
import SkillsMain from './components/Skills.vue';
import ProjectsMain from './components/Projects.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    HeroMain,
    AboutMain,
    FooterMain,
    SkillsMain,
    ProjectsMain,
    },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Poppins:wght@400;700&display=swap');
body{
  font-family: 'Inter', sans-serif;
  background-color: #E0E1DD;
}

</style>
