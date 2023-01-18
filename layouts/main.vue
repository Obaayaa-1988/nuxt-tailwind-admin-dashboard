<template>
    <div class="flex h-screen"> 
        <div class=""> 
            <SideBar />

        </div>
    
    <div class="">
        <div >
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