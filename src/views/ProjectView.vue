<template>
    <div class="project">
        <Navbar />
        <div class="container mx-auto h-[80vh]">
            <div class="mx-20 text-white">
                <div class="h-11"></div>
                <div class="mb-5">
                    <h1 class="font-bold text-right text-[30px] text-white">Project Portfolio</h1>
                    <p class="text-right font-light text-[20px] text-[#FCAEAE]">An <span class="text-white">informatic
                            engineering</span> student that is fully
                        knowledge-curious about <span class="text-white">System Analyst</span>.</p>
                    <p class="text-right font-light text-[20px] text-[#FCAEAE]">A person who highly enthused about
                        work and tasks ahead. Enjoy working
                        in a team group, understand the importance of being interactive, and getting to know others. Always
                        committed
                        to learning and self-development then consistently achieve better results.</p>
                </div>
                <div class="flex flex-row gap-5 mb-5">
                    <div class="basis-2/4 h-64 rounded-3xl hover:scale-105 bg-red-200">
                    </div>
                    <div class="basis-2/4 h-64 rounded-3xl hover:scale-105 bg-red-200">
                    </div>
                    <div class="basis-2/4 h-64 rounded-3xl hover:scale-105 bg-red-200">
                    </div>
                </div>
                <div class="float-right hover:text-[#FCAEAE] hover:cursor-pointer">
                    More Project →
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
</style>