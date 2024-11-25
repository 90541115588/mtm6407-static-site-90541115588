<template>
  <div>
    <!-- Global Navigation -->
    <Navbar />

    <!-- Main Content -->
    <main>
      <NuxtPage />
    </main>

    <!-- Global Footer -->
    <Footer />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';
import Footer from '~/components/Footer.vue';

export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
main {
  padding: 20px;
}
</style>
