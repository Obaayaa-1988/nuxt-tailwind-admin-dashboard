<template>
    <div class="flex h-screen"> 
    <SideBar />
    
    <div class="flex-1 overflow-hidden flex flex-col ">
        <div class="bg-slate-700 h-full">
            <Nuxt />
    
        </div>

        <!-- <div> 
            <DashFooter />
        </div>
     -->
    </div>
    </div>
  
</template>

<script>
import SideBar from '../components/SideBar.vue';
// import DashFooter from '../components/DashFooter.vue'
export default {
    name: 'MainLayout',

    components: {
        SideBar,
        // DashFooter,
    }

}
</script>

<style>

</style>