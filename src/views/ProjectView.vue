<template>
    <div class="project">
        <Navbar />
        <div class="container mx-auto h-[80vh]">
            <div class="mx-20 text-white">
                <div class="h-11"></div>
                <div class="mb-5">
                    <h1 class="font-bold text-right text-[30px] text-white">Project Portfolio</h1>
                    <p class="text-right font-light text-[20px] text-[#FCAEAE]">Explore <span class="text-white">the
                            works</span> that reflect my skills and passion. Each piece reflects <span class="text-white">my
                            growth and expertise</span>.</p>
                    <p class="text-right font-light text-[20px] text-[#FCAEAE]">
                        Take a look at my work. See how I bring ideas to life through thoughtful design and development.</p>
                </div>
                <div class="flex flex-row gap-5 mb-5">
                    <div class="basis-2/4 h-64 relative rounded-3xl bg-[#B8ACBA] shadow-glow overflow-hidden">
                        <img src="https://i.postimg.cc/hj9fxFZ0/image.png"
                            class="object-cover transition-transform hover:grayscale-0 duration-300 h-3/4 grayscale w-full rounded-t-3xl filter"
                            alt="">
                        <div class="px-4 py-2 text-black">
                            <p>Live source: <a class="hover:text-[#041349]"
                                    href="https://qs-movies.vercel.app/"><strong>click
                                        here </strong></a>
                            </p>
                            <p>Technology: <strong>Vue.js + Bootstrap</strong></p>
                        </div>
                    </div>

                    <div class="basis-2/4 h-64 relative rounded-3xl bg-[#B8ACBA] shadow-glow overflow-hidden">
                        <img src="https://i.postimg.cc/L54FCXWN/kambing-jpg.png"
                            class="object-cover hover:grayscale-0 h-3/4 w-full grayscale rounded-t-3xl" alt="">
                        <div class="px-4 py-2 text-black">
                            <p>Source: <a class="hover:text-[#041349]"
                                    href="https://github.com/Queniex/SPK-SMART"><strong>click here </strong></a></p>
                            <p>Technology: <strong>CI4 + Tailwind</strong></p>
                        </div>
                    </div>

                    <div class="basis-2/4 h-64 relative rounded-3xl bg-[#B8ACBA] shadow-glow overflow-hidden">
                        <img src="https://i.postimg.cc/8CcRhCLm/bhavana.png"
                            class="object-cover hover:grayscale-0 h-3/4 w-full grayscale rounded-t-3xl" alt="">
                        <div class="px-4 py-2 text-black">
                            <p>Source: <a class="hover:text-[#041349]"
                                    href="https://github.com/Queniex/Bhavana"><strong>click here </strong></a></p>
                            <p>Technology: <strong>Vue.js + Laravel + Tailwind</strong></p>
                        </div>
                    </div>
                </div>


                <div class="float-right hover:text-[#FCAEAE] hover:cursor-pointer">
                    <a href="https://github.com/Queniex?tab=repositories">More Project →</a>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
import Navbar from "@/components/Navbar.vue";

export default {
    name: 'ProjectView',
    components: {
        Navbar,
    }
}
</script>
  
<style scoped>
/* * {
    border: 1px red solid;
} */

.shadow-glow:hover {
    box-shadow: 0 0 7px rgba(255, 255, 255, 0.9);
}
</style>