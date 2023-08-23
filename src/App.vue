<template>
  <div id="app" :class="bodyClass">
    <router-view />
  </div>
</template>

<script>
export default {
  computed: {
    bodyClass() {
      // Tambahkan kelas berdasarkan nama route aktif
      return {
        'bg-[#B8ACBA]': this.$route.name === 'home',
        'bg-[#041349]': this.$route.name !== 'home'
      };
    }
  }
};
</script>

<style>
nav a.router-link-exact-active {
  color: white;
}

/* * {
  border: 1px solid red;
} */
</style>
