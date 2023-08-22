<template>
    <div class="contact">
        <Navbar />
        <div class="container mx-auto">
            <div class="mx-20 text-white">
                <div class="mt-5 h-[60vh] mb-5 flex justify-center items-center">
                    <div class="text-center">
                        <h1 class="font-bold text-[32px] text-[#FCAEAE] leading-[0.9]">Let's be friend</h1>
                        <h3 class="font-light text-[30px] text-white leading-[1.2]">Follow me!</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
import Navbar from "@/components/Navbar.vue";

export default {
    name: 'ContactView',
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