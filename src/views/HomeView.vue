<template>
  <Navbar />
  <div class="home">
    <h1>Homepage</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue';

export default {
  name: 'HomeView',
  components: {
    Navbar
  }
}
</script>
