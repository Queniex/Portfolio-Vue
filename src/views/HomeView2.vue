<template>
  <div class="home">
    <Navbar />
    <div class="container mx-auto h-[80vh]">
      <div class="mx-20 text-white">

        <div class="w-full bg-[#0B2447] rounded-3xl mb-2">
          <div class="flex justify-center h-20 items-center">
            <div class="typing-demo">
              Welcome to my personal website!
            </div>
          </div>
        </div>

        <div class="flex justify-center items-center">
          <div class="flex">
            <div class="w-2/3 flex justify-center items-center">
              <img class="" src="../assets/profilee.png" width="400px" alt="">
            </div>
            <div class="w-3/3 h-[55vh] my-4 flex justify-center items-center animate-float">
              <div class="m-auto leading-normal">

                <p class="text-[25px] font-[500] text-[#19376D] leading-[0.9]">Hi, I'm <span
                    class="text-black text-[40px] font-[700]">FILDZAH</span>.</p>
                <p class="text-[30px] font-[500] text-[#19376D] leading-[1.3]">Backend Developer Enthusiast</p>
                <p class="text-[30px] font-[500] text-black leading-[0.9]">Lorem ipsum dolor sit, amet consectetur
                  adipisicing elit. Culpa, et?</p>
                <!-- <div class="flex gap-3 justify-around mt-3">
                  <button
                    class="w-3/5 rounded-full text-[#19376D] border-2 border-[#19376D] text-[25px] font-[700] hover:bg-[#19376D] hover:text-black"><router-link
                      to="/about">About</router-link></button>
                  <button
                    class="w-2/5 rounded-full bg-[#19376D] text-[25px] font-[700] text-black hover:bg-black hover:text-[#F66]"><a
                      href="https://drive.google.com/file/d/1zRr7K0WNQwWUCjFOtSIviVDKz-u-S6ZF/view?usp=sharing"
                      target="_blank">Resume</a></button>
                </div> -->
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
  },
}
</script>

<style scoped>
/* * {
  border: 1px red solid;
} */

@keyframes float {

  0%,
  100% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-10px);
  }
}

.animate-float {
  animation: float 2s ease-in-out infinite;
}

.typing-demo {
  width: 28ch;
  animation: typing 2s steps(22), blink .5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-size: 40px;
  font-weight: 500;
  color: white;
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

.home {
  background-image: url('image.pnghttps://i.pinimg.com/564x/29/bf/d3/29bfd3320131a1e0681dd44576bd9f50.jpg');
}
</style>