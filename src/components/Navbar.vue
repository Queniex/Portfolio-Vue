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
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-white hover:text-[#FCAEAE] hover:cursor-pointer"
                            to="/">Home</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-white hover:text-[#FCAEAE] hover:cursor-pointer"
                            to="/about">About</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-white hover:text-[#FCAEAE] hover:cursor-pointer"
                            to="/project">Project</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-white hover:text-[#FCAEAE] hover:cursor-pointer"
                            to="/contact">Contact</router-link>
                        <!-- <div class="w-[7vw] h-11 bg-[#FCAEAE]"></div> -->
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

a.router-link-exact-active {
    color: #FCAEAE;
}
</style>
  