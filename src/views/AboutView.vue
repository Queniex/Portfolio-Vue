<template>
  <div class="about">
    <Navbar />
    <div class="container mx-auto h-[80vh]">
      <div class="mx-20 text-white">
        <div class="h-11"></div>
        <div class="mb-5">
          <h1 class="font-bold text-[30px] text-white">About Me</h1>
          <p class="text-justify font-light text-[20px] text-[#FCAEAE]">An <span class="text-white">informatic
              engineering</span> student that is fully
            knowledge-curious about <span class="text-white">System Analyst</span>.</p>
          <p class="text-justify font-light text-[20px] text-[#FCAEAE]">A person who highly enthused about
            work and tasks ahead. Enjoy working
            in a team group, understand the importance of being interactive, and getting to know others. Always committed
            to learning and self-development then consistently achieve better results.</p>
        </div>
        <div class="flex gap-3 justify-around mt-10">
          <div class="w-full mb-3">
            <div class="bg-white h-56 rounded-3xl">
              <div class="text-center pt-2">
                <h1 class="text-[30px] font-bold text-black">List of Tools</h1>
              </div>
              <div class="flex justify-center gap-5 mx-3 mb-3 mt-3">
                <div class="h-14 w-20 bg-black rounded-lg"></div>
                <div class="h-14 w-20 bg-black rounded-lg"></div>
                <div class="h-14 w-20 bg-black rounded-lg"></div>
                <div class="h-14 w-20 bg-black rounded-lg"></div>
                <div class="h-14 w-20 bg-black rounded-lg"></div>
              </div>
              <div class="flex justify-center gap-5 mx-3">
                <div class="h-14 w-20 bg-black rounded-lg"></div>
                <div class="h-14 w-20 bg-black rounded-lg"></div>
                <div class="h-14 w-20 bg-black rounded-lg"></div>
                <div class="h-14 w-20 bg-black rounded-lg"></div>
                <div class="h-14 w-20 bg-black rounded-lg"></div>
              </div>
            </div>
          </div>
          <div class="w-full mb-2">
            <div class="mx-2">
              <p class="text-justify mt-4 font-light text-[#FCAEAE]">Lorem ipsum, dolor sit amet consectetur adipisicing
                elit. Rerum
                obcaecati, quo non maiores debitis nisi
                mollitia, natus facere amet blanditiis quis delectus modi? Iste veritatis non amet quas culpa praesentium
                quaerat neque voluptas ratione, rerum facere ab consequuntur libero dolor ipsum ipsam dolores eveniet
                dolorem distinctio modi repellat. Sunt, eveniet ut labore deleniti, alias at qui voluptatum nihil quaerat
                aliquid et veritatis nisi dignissimos eos molestias consectetur nobis amet deserunt expedita nesciunt
                facere aspernatur! Eius, similique ut molestias quam nihil quaerat minus alias</p>
            </div>
          </div>
        </div>

        <div class="flex justify-around mt-7">
          <div class="w-full">
            <div class="mx-2">
              <p class="text-justify font-light text-[#FCAEAE]">Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Rerum
                obcaecati, quo non maiores debitis nisi
                mollitia, natus facere amet blanditiis quis delectus modi? Iste veritatis non amet quas culpa praesentium
                quaerat neque voluptas ratione, rerum facere ab consequuntur libero dolor ipsum ipsam dolores eveniet
                dolorem distinctio modi repellat. Sunt, eveniet ut labore deleniti, alias at qui voluptatum nihil quaerat
                aliquid et veritatis nisi dignissimos eos molestias consectetur nobis amet deserunt expedita nesciunt
                facere aspernatur! Eius, similique ut molestias quam nihil quaerat minus alias</p>
            </div>
          </div>
          <!-- <div class="w-full flex justify-center items-center">
            <span class="font-bold text-[30px]">See <button
                class="bg-[#FCAEAE] hover:bg-transparent hover:text-[#FCAEAE] text-black px-1 rounded-2xl">My
                Projects
              </button> So
              Far</span>
          </div> -->
          <div class="w-full mb-3">
            <div class="text-center pt-2">
              <h1 class="text-[30px] font-bold text-white">My Fav Tools</h1>
            </div>
            <div class="flex justify-center gap-5 mx-3 mb-3 mt-3">
              <div class="h-14 w-20 bg-white rounded-lg"></div>
              <div class="h-14 w-20 bg-white rounded-lg"></div>
              <div class="h-14 w-20 bg-white rounded-lg"></div>
              <div class="h-14 w-20 bg-white rounded-lg"></div>
              <div class="h-14 w-20 bg-white rounded-lg"></div>
            </div>
            <div class="flex justify-center gap-5 mx-3">
              <div class="h-14 w-20 bg-white rounded-lg"></div>
              <div class="h-14 w-20 bg-white rounded-lg"></div>
              <div class="h-14 w-20 bg-white rounded-lg"></div>
              <div class="h-14 w-20 bg-white rounded-lg"></div>
              <div class="h-14 w-20 bg-white rounded-lg"></div>
            </div>
          </div>
        </div>

        <div class="h-10"></div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: 'AboutView',
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