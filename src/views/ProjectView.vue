<template>
    <div class="project">
        <Navbar />
        <div class="container mx-auto h-[80vh]">
            <div class="mx-20 text-white">
                <div class="h-11"></div>
                <div class="mb-5">
                    <h1 class="font-bold text-right text-[30px] text-white">Project Portfolio</h1>
                    <p class="text-right font-light text-[20px] text-[#FCAEAE]">Lorem <span class="text-white">ipsum
                            dolor.</span> Sint suscipit fugit sit neque ea aut
                        nobis, labore nulla commodi tempore <span class="text-white">commodi</span>.</p>
                    <p class="text-right font-light text-[20px] text-[#FCAEAE]">
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sint suscipit fugit sit neque ea aut
                        nobis, labore nulla commodi tempore?</p>
                </div>
                <div class="flex flex-row gap-5 mb-5">
                    <div class="basis-2/4 h-64 relative rounded-3xl bg-red-200 hover:shadow-glow overflow-hidden">
                        <img src="https://i.pinimg.com/736x/be/0e/e1/be0ee121138774536f7475109c5c590d.jpg"
                            class="object-cover transition-transform duration-300 hover:scale-105 h-2/3 w-full rounded-t-3xl filter hover:blur-sm"
                            alt="">
                        <div
                            class="absolute flex items-center justify-center opacity-0 hover:opacity-100 transition-opacity duration-300">
                            <p class="text-center text-white p-4 bg-black bg-opacity-50">Lorem ipsum dolor sit amet
                                consectetur adipisicing elit. Nihil repellat error odit a nam animi asperiores natus,
                                earum quam aut at ipsa omnis possimus amet modi incidunt impedit nemo!</p>
                        </div>
                    </div>

                    <div class="basis-2/4 h-64 rounded-3xl bg-red-200 shadow-glow">
                        <img src="https://i.pinimg.com/736x/be/0e/e1/be0ee121138774536f7475109c5c590d.jpg"
                            class="object-cover h-2/3 w-full rounded-t-3xl" alt="">
                    </div>
                    <div class="basis-2/4 h-64 rounded-3xl bg-red-200 shadow-glow">
                        <img src="https://i.pinimg.com/736x/be/0e/e1/be0ee121138774536f7475109c5c590d.jpg"
                            class="object-cover h-2/3 w-full rounded-t-3xl" alt="">
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