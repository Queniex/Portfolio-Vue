<template>
  <div class="home">
    <Navbar />
    <div class="container mx-auto bg-black">
      <h1 class="text-gray-50"> Hello</h1>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: 'HomeView',
  components: {
    Navbar,
  }
}
</script>
