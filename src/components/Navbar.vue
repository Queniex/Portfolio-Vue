<template>
    <div class="navbar text-white">
        <div class="w-full h-[20vh]">
            <div class="container mx-auto h-[100%] flex">
                <div class="mx-20 my-2 h-[100%] w-[100%] flex justify-center items-center">

                    <div class="w-1/3 bg-[#B8ACBA] absolute left-0 rounded-e-full h-10"></div>
                    <div class="bg-[#041349] h-16 w-full rounded-full flex justify-center items-center gap-5">
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-[#B8ACBA] hover:text-[#black] hover:cursor-pointer"
                            to="/">Home</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-[#B8ACBA] hover:text-[#black] hover:cursor-pointer"
                            to="/about">About</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-[#B8ACBA] hover:text-[#black] hover:cursor-pointer"
                            to="/project">Project</router-link>
                        <router-link
                            class="nav-link text-[1.7rem] font-[700] text-[#B8ACBA] hover:text-[#black] hover:cursor-pointer"
                            to="/contact">Contact</router-link>

                    </div>

                    <!-- <div class="w-2/3 flex gap-10 justify-end">
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

                    </div> -->
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
    color: white;
    text-decoration: underline;
    text-underline-offset: 30%;
}
</style>
  