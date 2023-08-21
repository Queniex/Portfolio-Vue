<template>
    <div class="navbar text-white">
        <div class="w-full h-[20vh]">
            <div class="container mx-auto h-[100%] flex">
                <div class="mx-20 my-2 h-[100%] w-[100%] flex justify-center items-center">
                    <div class="w-1/3">
                        <h1 class="text-[1.7rem] font-[700] text-white">FILDZAH<span
                                class="text-[2rem] font-[700] text-[#FCAEAE]">.</span>
                        </h1>
                    </div>
                    <div class="w-2/3 flex gap-10 justify-end">
                        <h1 class="text-[1.7rem] font-[700] text-white hover:text-[#FCAEAE] hover:cursor-pointer">
                            Home
                        </h1>
                        <h1 class="text-[1.7rem] font-[700] text-white hover:text-[#FCAEAE] hover:cursor-pointer">
                            About
                        </h1>
                        <h1 class="text-[1.7rem] font-[700] text-white hover:text-[#FCAEAE] hover:cursor-pointer">
                            Project
                        </h1>
                        <h1
                            class="text-[1.7rem] font-[700] text-white hover:ease-in duration-300 hover:text-[#FCAEAE] hover:cursor-pointer">
                            Contact
                        </h1>
                        <div class="w-[7vw] h-11 bg-[#FCAEAE]"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    name: 'Navbar',
    props: {
        msg: String
    }
}
</script>
  
<style scoped>
/* * {
    border: 1px red solid;
} */
</style>
  