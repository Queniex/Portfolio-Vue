<template>
  <div class="home">
    <Navbar />
    <div class="mx-32 text-white flex gap-3 justify-start">
      <div class="w-2/3 bg-[#B8ACBA] h-[80vh] flex flex-col justify-center">
        <p class="text-[20px] font-medium text-[#576CBC] leading-[0.6]">Hi, welcome!</p>
        <div class="flex">
          <p class="text-[50px] self-center mr-3 font-bold text-[#041349] leading-[0.8]">I'm
          </p>
          <div class="typing-animate">Fildzah.</div>
        </div>
        <p class="text-[40px] font-bold text-[#041349] leading-[0.5] mb-3">Frontend Web Enthusiast</p>
        <p class="text-[20px] font-medium text-[#041349] leading-[1.5]">Want to get to know me better? Let's get familiar!
        </p>

        <div class="flex gap-3 justify-left mt-4">
          <!-- <button
            class="w-2/5 rounded-full text-[#041349] border-2 border-[#041349] text-[25px] font-[700] hover:bg-[#041349] hover:text-white"><router-link
              to="/about">About</router-link></button> -->
          <button
            class="w-2/5 rounded-full bg-[#041349] text-[25px] font-[700] text-white hover:bg-transparent hover:text-[#041349]"><a
              href="https://drive.google.com/file/d/1QaydqRnvtdW0En3bNK1posl-Q9XxxlEf/view?usp=sharing"
              target="_blank">Download CV</a></button>
        </div>
      </div>
      <div class="w-2/3 bg-[#041349] h-[60vh] self-center flex items-center justify-center">
        <!-- <img src="https://i.postimg.cc/Kv4mhS7s/Photo-Profile.png" class="object-cover h-[55vh]" alt=""> -->
        <img :src="require('@/assets/images/Photo-Profile.png')" class="object-cover h-[55vh]" alt="Kambing Image" />
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
  },
}
</script>

<style scoped>
/* * {
  border: 1px red solid;
} */

@keyframes float2 {

  0%,
  100% {
    transform: translateY(0);
  }


  50% {
    transform: translateY(-10px);
  }

}

@keyframes float1 {

  0%,
  100% {
    transform: translateY(-10px);
  }

  50% {
    transform: translateY(0px);
  }
}

.animate-float1 {
  animation: float1 2s ease-in-out infinite;
}

.animate-float2 {
  animation: float2 2s ease-in-out infinite;
}

.typing-animate {
  width: 6.5ch;
  animation: typing 2s steps(10), blink .5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-size: 50px;
  font-weight: bold;
  color: black;
}

@keyframes typing {
  from {
    width: 0
  }
}

@keyframes blink {
  50% {
    border-color: transparent
  }
}
</style>