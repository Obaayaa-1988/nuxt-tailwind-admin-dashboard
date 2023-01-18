<template>
    <div > 
        <!------------main content of dashboard start------------------->
        <!---------------mini header start------------------------------>
        <div class="flex justify-evenly " >
            <div class="flex justify-center pt-4">
                <div class="mb-3 xl:w-96">
                    <div class="input-group relative flex flex-wrap items-stretch w-full mb-4">
                        <input type="search"
                            class="form-control relative flex-auto min-w-0 block w-full px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                            placeholder="Search" aria-label="Search" aria-describedby="button-addon2"/>
                        
                    </div>
                </div>
            </div>


            <!-----------------beginning of dropdown menu-------------->

                <div class="flex justify-center">
                    <div>
                        <div class="dropdown relative pt-4">
                            <button class="
                          dropdown-toggle
                          px-6
                          py-2.5
                          bg-cyan-400
                          text-white
                          font-medium
                          text-xs
                          leading-tight
                          uppercase
                          rounded
                          shadow-md
                          hover:bg-blue-700 hover:shadow-lg
                          focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0
                          active:bg-blue-800 active:shadow-lg active:text-white
                          transition
                          duration-150
                          ease-in-out
                          flex
                          items-center
                          whitespace-nowrap
                        " type="button" id="dropdownMenuButton1h" data-bs-toggle="dropdown" aria-expanded="false">
                            Sample Menu
                                <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="caret-down" class="w-2 ml-2"
                                    role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
                                    <path fill="currentColor"
                                        d="M31.3 192h257.3c17.8 0 26.7 21.5 14.1 34.1L174.1 354.8c-7.8 7.8-20.5 7.8-28.3 0L17.2 226.1C4.6 213.5 13.5 192 31.3 192z">
                                    </path>
                                </svg>
                            </button>
                            <ul class="
                          dropdown-menu
                          min-w-max
                          absolute
                          hidden
                          bg-white
                          text-base
                          z-50
                          float-left
                          py-2
                          list-none
                          text-left
                          rounded-lg
                          shadow-lg
                          mt-1
                          hidden
                          m-0
                          bg-clip-padding
                          border-none
                        " aria-labelledby="dropdownMenuButton1h">
                                <h6 class="
                            text-gray-500
                            font-semibold
                            text-sm
                            py-2
                            px-4
                            block
                            w-full
                            whitespace-nowrap
                            bg-transparent
                          ">
                                    Sample Menu
                                </h6>
                                <li>
                                    <a class="
                              dropdown-item
                              text-sm
                              py-2
                              px-4
                              font-normal
                              block
                              w-full
                              whitespace-nowrap
                              bg-transparent
                              text-gray-700
                              hover:bg-gray-100
                            " href="#">Action</a>
                                </li>
                                <li>
                                    <a class="
                              dropdown-item
                              text-sm
                              py-2
                              px-4
                              font-normal
                              block
                              w-full
                              whitespace-nowrap
                              bg-transparent
                              text-gray-700
                              hover:bg-gray-100
                            " href="#">Another action</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                
            <!--------------------------end of dropdow menu-------------->

            <!--------------------------start of user profile svg icon-------------->
            <div class="flex justify-between"> 
                <div><img src="images/User.jpg" alt="PanCake" class="w-14 h-14 object-cover rounded-full pt-2" /> </div>
                <div class="pt-4 text-white font-mono font-bold ml-2"> John Doe</div>
            </div>

            <!--------------------------end of user profile svg icon -------------->
            <!--------------------svg icons--------------start---------------------->
            <div> 
                <svg xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512" class="w-10 h-10 fill-white pt-4 cursor-pointer font-semibold" >
                    <path
                        d="M256 512c141.4 0 256-114.6 256-256S397.4 0 256 0S0 114.6 0 256S114.6 512 256 512zm50.7-186.9L162.4 380.6c-19.4 7.5-38.5-11.6-31-31l55.5-144.3c3.3-8.5 9.9-15.1 18.4-18.4l144.3-55.5c19.4-7.5 38.5 11.6 31 31L325.1 306.7c-3.2 8.5-9.9 15.1-18.4 18.4zM288 256c0-17.7-14.3-32-32-32s-32 14.3-32 32s14.3 32 32 32s32-14.3 32-32z" />
                </svg>
                

            </div>
            <div> 

                <svg xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512" class="w-10 h-10 fill-white pt-4 cursor-pointer font-semibold" >
                    <path
                        d="M48 64C21.5 64 0 85.5 0 112c0 15.1 7.1 29.3 19.2 38.4L236.8 313.6c11.4 8.5 27 8.5 38.4 0L492.8 150.4c12.1-9.1 19.2-23.3 19.2-38.4c0-26.5-21.5-48-48-48H48zM0 176V384c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V176L294.4 339.2c-22.8 17.1-54 17.1-76.8 0L0 176z" />
                </svg>
                

            </div>
            <div> 
                <svg xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512" class="w-10 h-10 fill-white pt-4 cursor-pointer font-semibold">
                    <path
                        d="M128 0c17.7 0 32 14.3 32 32V64H288V32c0-17.7 14.3-32 32-32s32 14.3 32 32V64h48c26.5 0 48 21.5 48 48v48H0V112C0 85.5 21.5 64 48 64H96V32c0-17.7 14.3-32 32-32zM0 192H448V464c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V192zm64 80v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H80c-8.8 0-16 7.2-16 16zm128 0v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H208c-8.8 0-16 7.2-16 16zm144-16c-8.8 0-16 7.2-16 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H336zM64 400v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H80c-8.8 0-16 7.2-16 16zm144-16c-8.8 0-16 7.2-16 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H208zm112 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H336c-8.8 0-16 7.2-16 16z" />
                </svg>
                

            </div>

            <!----------------------------svg icons end---------------------------------->
        </div>

        <!---------------mini header start---------------------------------------------->

        <!-------------------------sub header ------------------start----------------->
        <div class="flex justify-between px-28 py-12"> 
            <div> 
                <h1 class="text-white text-3xl font mono font-bold"> Overview</h1>
            
            </div>

            <div>    
             <button class=" font-mono text-center rounded font-extrabold  bg-white px-4 py-2"> <h1>Ash Dashboard</h1></button>
            </div>
        </div>
        <!-------------------------sub header ------------------end------------------->


        <!----------------------------------------start-- dark cards----------------->

<section class="rounded-b-3xl w-full h-3/4  px-16 py-6 md:col-span-2 ">
    <div class=" flex justify-evenly  ">
        <nuxt-link to="/Running">
            <div class="bg-stone-800  w-80 h-48 rounded-3xl overflow-hidden shadow-md relative  cursor-pointer py-8 text-center">
                <div class="flex justify-around"> 

                    <div>
                        <h2 class="bg-green-400 px-6 py-1 rounded-md">200</h2>
                    
                    </div>
                    
                    <div class="bg-white py-2 px-2 ">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                            class="w-4 h-4 "><!--! Font Awesome Pro 6.2.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                            <path
                                d="M328 160h-144C170.8 160 160 170.8 160 184v144C160 341.2 170.8 352 184 352h144c13.2 0 24-10.8 24-24v-144C352 170.8 341.2 160 328 160zM256 0C114.6 0 0 114.6 0 256s114.6 256 256 256s256-114.6 256-256S397.4 0 256 0zM256 464c-114.7 0-208-93.31-208-208S141.3 48 256 48s208 93.31 208 208S370.7 464 256 464z" />
                        </svg>
                    
                    </div>
                </div>


                <div class="flex justify-around pt-8"> 
                
                    <div>
                        <h1 class="text-gray-300 font-mono text-xs font-thin"> Clients</h1>
                        <h2 class="text-white font-mono text-2xl "> 512 </h2>
                    </div>
                
                    <div>
                        <svg xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 640 512" class="w-9 h-9 fill-green-600">
                            <path
                                d="M352 128c0 70.7-57.3 128-128 128s-128-57.3-128-128S153.3 0 224 0s128 57.3 128 128zM0 482.3C0 383.8 79.8 304 178.3 304h91.4C368.2 304 448 383.8 448 482.3c0 16.4-13.3 29.7-29.7 29.7H29.7C13.3 512 0 498.7 0 482.3zM609.3 512H471.4c5.4-9.4 8.6-20.3 8.6-32v-8c0-60.7-27.1-115.2-69.8-151.8c2.4-.1 4.7-.2 7.1-.2h61.4C567.8 320 640 392.2 640 481.3c0 17-13.8 30.7-30.7 30.7zM432 256c-31 0-59-12.6-79.3-32.9C372.4 196.5 384 163.6 384 128c0-26.8-6.6-52.1-18.3-74.3C384.3 40.1 407.2 32 432 32c61.9 0 112 50.1 112 112s-50.1 112-112 112z" />
                        </svg>
                    </div>
                
                
                
                </div>
                

            </div>
        </nuxt-link>

        <nuxt-link to="/Running">
            <div class="bg-stone-800  w-80 h-48 rounded-3xl overflow-hidden shadow-md relative  cursor-pointer py-8 text-center">
                <div class="flex justify-around"> 

                    <div>
                        <h2 class="bg-red-500 px-6 py-1 rounded-md">200</h2>
                    
                    </div>
                    
                    <div class="bg-white py-2 px-2 rounded">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                            class="w-4 h-4 "><!--! Font Awesome Pro 6.2.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                            <path
                                d="M328 160h-144C170.8 160 160 170.8 160 184v144C160 341.2 170.8 352 184 352h144c13.2 0 24-10.8 24-24v-144C352 170.8 341.2 160 328 160zM256 0C114.6 0 0 114.6 0 256s114.6 256 256 256s256-114.6 256-256S397.4 0 256 0zM256 464c-114.7 0-208-93.31-208-208S141.3 48 256 48s208 93.31 208 208S370.7 464 256 464z" />
                        </svg>
                        
                    </div>
                </div>


                <div class="flex justify-around pt-8"> 
                
                    <div>
                        <h1 class="text-gray-300 font-mono text-xs font-thin">Sales</h1>
                        <h2 class="text-white font-mono text-2xl "> $17,777 </h2>
                    </div>
                
                    <div>
                        <svg xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 576 512" class="w-9 h-9 fill-cyan-600">
                            <path
                                d="M0 24C0 10.7 10.7 0 24 0H69.5c22 0 41.5 12.8 50.6 32h411c26.3 0 45.5 25 38.6 50.4l-41 152.3c-8.5 31.4-37 53.3-69.5 53.3H170.7l5.4 28.5c2.2 11.3 12.1 19.5 23.6 19.5H488c13.3 0 24 10.7 24 24s-10.7 24-24 24H199.7c-34.6 0-64.3-24.6-70.7-58.5L77.4 54.5c-.7-3.8-4-6.5-7.9-6.5H24C10.7 48 0 37.3 0 24zM128 464a48 48 0 1 1 96 0 48 48 0 1 1 -96 0zm336-48a48 48 0 1 1 0 96 48 48 0 1 1 0-96z" />
                        </svg>
                       
                    </div>
                
                
                
                </div>
                

            </div>
        </nuxt-link>
        <nuxt-link to="/Running">
            <div class="bg-stone-800  w-80 h-48 rounded-3xl overflow-hidden shadow-md relative  cursor-pointer py-8 text-center">
                <div class="flex justify-around"> 

                    <div>
                        <h2 class="bg-yellow-500 px-6 py-1 rounded-md">conference</h2>
                    
                    </div>
                    
                    <div class="bg-white py-2 px-2 rounded ">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                            class="w-4 h-4 "><!--! Font Awesome Pro 6.2.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                            <path
                                d="M328 160h-144C170.8 160 160 170.8 160 184v144C160 341.2 170.8 352 184 352h144c13.2 0 24-10.8 24-24v-144C352 170.8 341.2 160 328 160zM256 0C114.6 0 0 114.6 0 256s114.6 256 256 256s256-114.6 256-256S397.4 0 256 0zM256 464c-114.7 0-208-93.31-208-208S141.3 48 256 48s208 93.31 208 208S370.7 464 256 464z" />
                        </svg>
                    
                    </div>
                </div>


                <div class="flex justify-around pt-8"> 
                
                    <div>
                        <h1 class="text-gray-300 font-mono text-xs font-thin"> Performance</h1>
                        <h2 class="text-white font-mono text-2xl "> %256 </h2>
                    </div>
                
                    <div>
                        <svg xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 448 512" class="w-9 h-9 fill-red-600"><!--! Font Awesome Pro 6.2.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                            <path
                                d="M160 80c0-26.5 21.5-48 48-48h32c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48H208c-26.5 0-48-21.5-48-48V80zM0 272c0-26.5 21.5-48 48-48H80c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V272zM368 96h32c26.5 0 48 21.5 48 48V432c0 26.5-21.5 48-48 48H368c-26.5 0-48-21.5-48-48V144c0-26.5 21.5-48 48-48z" />
                        </svg>
                        
                    </div>
                
                
                
                </div>
                

            </div>
        </nuxt-link>
        <nuxt-link to="/Running">
            <div class="bg-stone-800  w-80 h-48 rounded-3xl overflow-hidden shadow-md relative  cursor-pointer py-8 text-center">
                <div class="flex justify-around"> 

                    <div>
                        <h2 class="bg-cyan-400 px-6 py-1 rounded-md">Last 24 Hours</h2>
                    
                    </div>
                    
                    <div class="bg-white py-2 px-2 rounded ">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"
                            class="w-4 h-4 "><!--! Font Awesome Pro 6.2.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                            <path
                                d="M328 160h-144C170.8 160 160 170.8 160 184v144C160 341.2 170.8 352 184 352h144c13.2 0 24-10.8 24-24v-144C352 170.8 341.2 160 328 160zM256 0C114.6 0 0 114.6 0 256s114.6 256 256 256s256-114.6 256-256S397.4 0 256 0zM256 464c-114.7 0-208-93.31-208-208S141.3 48 256 48s208 93.31 208 208S370.7 464 256 464z" />
                        </svg>
                    
                    </div>
                </div>


                <div class="flex justify-around pt-8"> 
                
                    <div>
                        <h1 class="text-gray-300 font-mono text-xs font-thin">Alerts</h1>
                        <h2 class="text-white font-mono text-2xl "> %256 </h2>
                    </div>
                
                    <div>
                        <svg xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 448 512" class="w-9 h-9 fill-yellow-500"><!--! Font Awesome Pro 6.2.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
                            <path
                                d="M224 0c-17.7 0-32 14.3-32 32V51.2C119 66 64 130.6 64 208v18.8c0 47-17.3 92.4-48.5 127.6l-7.4 8.3c-8.4 9.4-10.4 22.9-5.3 34.4S19.4 416 32 416H416c12.6 0 24-7.4 29.2-18.9s3.1-25-5.3-34.4l-7.4-8.3C401.3 319.2 384 273.9 384 226.8V208c0-77.4-55-142-128-156.8V32c0-17.7-14.3-32-32-32zm45.3 493.3c12-12 18.7-28.3 18.7-45.3H224 160c0 17 6.7 33.3 18.7 45.3s28.3 18.7 45.3 18.7s33.3-6.7 45.3-18.7z" />
                        </svg>
                        
                        
                    </div>
                
                
                
                </div>
                

            </div>
        </nuxt-link>

       
    </div>

   
</section>



        <!--------------------------------------end--of dark cards------------------->
        <!--------------------------------------start--of main cards------------------->
        <section>
            <div> 

            </div> 




        </section>




        <!--------------------------------------end--of main cards--------------------->



        <!------------main content of dashboard end----------------------------------->
       

    </div>
  
</template>

<script>
export default {
    name: 'HomePage',
    layout: 'main'

}
</script>

<style>

</style>