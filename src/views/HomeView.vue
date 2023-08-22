<template>
  <div class="home">
    <Navbar />
    <div class="container mx-auto h-[80vh]">
      <div class="mx-20 text-white">
        <div class="flex">
          <div class="w-2/3 flex justify-center items-center">
            <img class="" src="../assets/profile.png" width="500px" alt="">
          </div>
          <div class="w-2/3 h-[75vh] my-4 flex justify-center items-center">
            <div class="m-auto leading-normal">
              <p class="text-[20px] font-[250] text-[#FCAEAE] leading-[0.9]">Welcome to my personal website</p>
              <p class="text-[47px] font-[500] text-[#FCAEAE] leading-[1.2]">Hi, I'm <span
                  class="text-white">FILDZAH</span>.</p>
              <p class="text-[30px] font-[500] text-[#FCAEAE] leading-[0.9]">System Analyst Enthusiast
              </p>
              <div class="flex gap-3 justify-around mt-5">
                <button
                  class="w-3/5 rounded-full text-[#FCAEAE] border-2 border-[#FCAEAE] text-[25px] font-[700] hover:bg-[#FCAEAE] hover:text-black"><router-link
                    to="/about">About</router-link></button>
                <button
                  class="w-2/5 rounded-full bg-[#FCAEAE] text-[25px] font-[700] text-black hover:bg-black hover:text-[#F66]">Resume</button>
              </div>
            </div>
          </div>
        </div>
      </div>
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

<style scoped>
/* * {
  border: 1px red solid;
} */
</style>