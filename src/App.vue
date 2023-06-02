<template>
  <NavBar />
  <main>
    <HeroMain />
    <AboutMain />
  </main>
</template>

<script>
import NavBar from './components/Navbar.vue';
import HeroMain from './components/Hero.vue';
import AboutMain from './components/About.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    HeroMain,
    AboutMain
    },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Poppins:wght@400;700&display=swap');
body{
  font-family: 'Inter', sans-serif;
}

</style>
