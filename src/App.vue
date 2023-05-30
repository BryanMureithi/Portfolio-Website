<template>
  <NavBar />
</template>

<script>
import NavBar from './components/Navbar.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Poppins:wght@400;700&display=swap');
body{
  font-family: 'Inter', sans-serif;
}

</style>
