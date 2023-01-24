<template>
    <div class="flex h-full"> 
      <SideBar />
      <div class="flex-1 overflow-hidden flex flex-col">
        <div class="bg-slate-700">
            <Nuxt />
       </div>
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