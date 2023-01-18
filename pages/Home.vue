<template>
    <div > 
        <!------------main content of dashboard start------------------->
        <!---------------mini header start------------------------------>
        <div class="flex justify-evenly" >
            <div class="flex justify-center">
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
                        <div class="dropdown relative">
                            <button class="
                          dropdown-toggle
                          px-6
                          py-2.5
                          bg-blue-600
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
                                Dropdown header
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
                                    Dropdown header
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
                <div><img src="images/User.jpg" alt="PanCake" class="w-14 h-14 object-cover rounded-full" /> </div>
                <div class="pt-4"> John Doe</div>
            </div>

            <!--------------------------end of user profile svg icon -------------->
            <!--------------------svg icons--------------start---------------------->
            <div> 
                <svg xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512" class="w-10 h-10 text-black pt-4" >
                    <path
                        d="M256 512c141.4 0 256-114.6 256-256S397.4 0 256 0S0 114.6 0 256S114.6 512 256 512zm50.7-186.9L162.4 380.6c-19.4 7.5-38.5-11.6-31-31l55.5-144.3c3.3-8.5 9.9-15.1 18.4-18.4l144.3-55.5c19.4-7.5 38.5 11.6 31 31L325.1 306.7c-3.2 8.5-9.9 15.1-18.4 18.4zM288 256c0-17.7-14.3-32-32-32s-32 14.3-32 32s14.3 32 32 32s32-14.3 32-32z" />
                </svg>
                

            </div>
            <div> 

                <svg xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512" class="w-10 h-10 text-black pt-4" >
                    <path
                        d="M48 64C21.5 64 0 85.5 0 112c0 15.1 7.1 29.3 19.2 38.4L236.8 313.6c11.4 8.5 27 8.5 38.4 0L492.8 150.4c12.1-9.1 19.2-23.3 19.2-38.4c0-26.5-21.5-48-48-48H48zM0 176V384c0 35.3 28.7 64 64 64H448c35.3 0 64-28.7 64-64V176L294.4 339.2c-22.8 17.1-54 17.1-76.8 0L0 176z" />
                </svg>
                

            </div>
            <div> 
                <svg xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 448 512" class="w-10 h-10 text-black pt-4">
                    <path
                        d="M128 0c17.7 0 32 14.3 32 32V64H288V32c0-17.7 14.3-32 32-32s32 14.3 32 32V64h48c26.5 0 48 21.5 48 48v48H0V112C0 85.5 21.5 64 48 64H96V32c0-17.7 14.3-32 32-32zM0 192H448V464c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V192zm64 80v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H80c-8.8 0-16 7.2-16 16zm128 0v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H208c-8.8 0-16 7.2-16 16zm144-16c-8.8 0-16 7.2-16 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V272c0-8.8-7.2-16-16-16H336zM64 400v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H80c-8.8 0-16 7.2-16 16zm144-16c-8.8 0-16 7.2-16 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H208zm112 16v32c0 8.8 7.2 16 16 16h32c8.8 0 16-7.2 16-16V400c0-8.8-7.2-16-16-16H336c-8.8 0-16 7.2-16 16z" />
                </svg>
                

            </div>

            <!----------------------------svg icons end---------------------------------->
        </div>

        <!---------------mini header start------------------------------>
        <!------------main content of dashboard end----------------------->
       

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