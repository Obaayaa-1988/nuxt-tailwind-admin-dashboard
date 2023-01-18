<template>
    <div>
    
        <div class=" border-gray-200 dark:border-gray-700">
            <ul class="flex flex-wrap justify-evenly -mb-px text-sm font-medium text-center  dark:text-gray-400">
                <li class="mr-2">
                    <nuxt-link to="/" href="#"
                        class="inline-flex p-4 rounded-t-lg active  hover:text-gray-600 hover:border-gray-300 dark:hover:text-gray-300 group  aria-current= page">
                        <svg xmlns="http://www.w3.org/2000/svg" class="text-pink-600 font-extrabold mr-2 h-10 w-10"
                            fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
                        </svg>
                    </nuxt-link>
                </li>
    
                <li class="mr-2">
                    <nuxt-link to="/profile" class="inline-flex p-4  rounded-t-lg  group">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="w-10 h-10 text-indigo-600">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z" />
                        </svg>
    
                    </nuxt-link>
                </li>
    
    
    
                <li class="mr-2">
                    <nuxt-link to="/archive" class="inline-flex p-4  rounded-t-lg  group">
                        <svg class="w-10 h-10 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                            xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z">
                            </path>
                        </svg>
                    </nuxt-link>
                </li>
    
                <li class="mr-2">
                    <nuxt-link to="/store" class="inline-flex p-4 rounded-t-lg  dark:hover:text-gray-300 group">
                        <svg class="w-10 h-10 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                            xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M8 7H5a2 2 0 00-2 2v9a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-3m-1 4l-3 3m0 0l-3-3m3 3V4">
                            </path>
                        </svg>
                    </nuxt-link>
                </li>
    
            </ul>
        </div>
    
    
    </div>
  
</template>

<script>
export default {
    name: 'DashFooter',

}
</script>

<style>

</style>