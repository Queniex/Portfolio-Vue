<template>
    <div class="navbar text-white">
        <div class="w-full h-[20vh]">
            <div class="container mx-auto h-[100%] flex">
                <div class="mx-20 my-2 h-[100%] w-[100%] flex justify-center items-center">
                    <div class="w-1/3">
                        <h1 class="text-[1.7rem] font-[700] text-black">FILDZAH<span
                                class="text-[2rem] font-[700] text-[#19376D]">.</span>
                        </h1>
                    </div>

                    <div class="w-2/3 flex gap-10 justify-end">
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-[#0B2447] hover:text-[#black] hover:cursor-pointer"
                            to="/">Home</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-[#0B2447] hover:text-[#black] hover:cursor-pointer"
                            to="/about">About</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-[#0B2447] hover:text-[#black] hover:cursor-pointer"
                            to="/project">Project</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-[#0B2447] hover:text-[#black] hover:cursor-pointer"
                            to="/contact">Contact</router-link>
                        <!-- <button
                            class="text-[1.7rem] font-[700] px-1 bg-red-200 rounded-3xl text-black hover:bg-red-300 hover:text-[#F66]"
                            @click="playMusic">
                            <div class="h-11 w-11 rounded-full">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                    <path
                                        d="M12 13.5351V3H20V5H14V17C14 19.2091 12.2091 21 10 21C7.79086 21 6 19.2091 6 17C6 14.7909 7.79086 13 10 13C10.7286 13 11.4117 13.1948 12 13.5351ZM10 19C11.1046 19 12 18.1046 12 17C12 15.8954 11.1046 15 10 15C8.89543 15 8 15.8954 8 17C8 18.1046 8.89543 19 10 19Z">
                                    </path>
                                </svg>
                            </div>
                        </button> -->
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
    },
}
</script>
  
<style scoped>
/* * {
    border: 1px red solid;
} */

a.router-link-exact-active {
    color: black;
}
</style>
  