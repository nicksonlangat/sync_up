<template>
  <div class="">
     <div class="flex mt-4 gap-4 ml-4">
        <div class="w-[50px] bg-white ">
           <div class="flex cursor-pointer flex-col items-start gap-y-8 justify-start">
              <span class="rounded-full mt-20 bg-blue-500 px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 text-white h-6">
                    <path d="M4.5 4.5a3 3 0 00-3 3v9a3 3 0 003 3h8.25a3 3 0 003-3v-9a3 3 0 00-3-3H4.5zM19.94 18.75l-2.69-2.69V7.94l2.69-2.69c.944-.945 2.56-.276 2.56 1.06v11.38c0 1.336-1.616 2.005-2.56 1.06z" />
                 </svg>
              </span>
              <span class="rounded-full  hover:bg-blue-500 px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6  hover:text-white text-gray-600 h-6">
                    <path fill-rule="evenodd" d="M11.078 2.25c-.917 0-1.699.663-1.85 1.567L9.05 4.889c-.02.12-.115.26-.297.348a7.493 7.493 0 00-.986.57c-.166.115-.334.126-.45.083L6.3 5.508a1.875 1.875 0 00-2.282.819l-.922 1.597a1.875 1.875 0 00.432 2.385l.84.692c.095.078.17.229.154.43a7.598 7.598 0 000 1.139c.015.2-.059.352-.153.43l-.841.692a1.875 1.875 0 00-.432 2.385l.922 1.597a1.875 1.875 0 002.282.818l1.019-.382c.115-.043.283-.031.45.082.312.214.641.405.985.57.182.088.277.228.297.35l.178 1.071c.151.904.933 1.567 1.85 1.567h1.844c.916 0 1.699-.663 1.85-1.567l.178-1.072c.02-.12.114-.26.297-.349.344-.165.673-.356.985-.57.167-.114.335-.125.45-.082l1.02.382a1.875 1.875 0 002.28-.819l.923-1.597a1.875 1.875 0 00-.432-2.385l-.84-.692c-.095-.078-.17-.229-.154-.43a7.614 7.614 0 000-1.139c-.016-.2.059-.352.153-.43l.84-.692c.708-.582.891-1.59.433-2.385l-.922-1.597a1.875 1.875 0 00-2.282-.818l-1.02.382c-.114.043-.282.031-.449-.083a7.49 7.49 0 00-.985-.57c-.183-.087-.277-.227-.297-.348l-.179-1.072a1.875 1.875 0 00-1.85-1.567h-1.843zM12 15.75a3.75 3.75 0 100-7.5 3.75 3.75 0 000 7.5z" clip-rule="evenodd" />
                 </svg>
              </span>
              <span class="rounded-full transition-colors duration-300 hover:bg-blue-500 px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 transition-colors duration-300 hover:text-white text-gray-600 h-6">
                    <path fill-rule="evenodd" d="M5.25 9a6.75 6.75 0 0113.5 0v.75c0 2.123.8 4.057 2.118 5.52a.75.75 0 01-.297 1.206c-1.544.57-3.16.99-4.831 1.243a3.75 3.75 0 11-7.48 0 24.585 24.585 0 01-4.831-1.244.75.75 0 01-.298-1.205A8.217 8.217 0 005.25 9.75V9zm4.502 8.9a2.25 2.25 0 104.496 0 25.057 25.057 0 01-4.496 0z" clip-rule="evenodd" />
                 </svg>
              </span>
              <span class="rounded-full transition-colors duration-300 bg-blue-500 px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 transition-colors duration-300 text-white h-6">
                    <path fill-rule="evenodd" d="M4.848 2.771A49.144 49.144 0 0112 2.25c2.43 0 4.817.178 7.152.52 1.978.292 3.348 2.024 3.348 3.97v6.02c0 1.946-1.37 3.678-3.348 3.97a48.901 48.901 0 01-3.476.383.39.39 0 00-.297.17l-2.755 4.133a.75.75 0 01-1.248 0l-2.755-4.133a.39.39 0 00-.297-.17 48.9 48.9 0 01-3.476-.384c-1.978-.29-3.348-2.024-3.348-3.97V6.741c0-1.946 1.37-3.68 3.348-3.97zM6.75 8.25a.75.75 0 01.75-.75h9a.75.75 0 010 1.5h-9a.75.75 0 01-.75-.75zm.75 2.25a.75.75 0 000 1.5H12a.75.75 0 000-1.5H7.5z" clip-rule="evenodd" />
                 </svg>
              </span>
              <span class="rounded-full transition-colors duration-300 hover:bg-blue-500 px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 transition-colors duration-300 hover:text-white text-gray-600 h-6">
                    <path fill-rule="evenodd" d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25zM12.75 6a.75.75 0 00-1.5 0v6c0 .414.336.75.75.75h4.5a.75.75 0 000-1.5h-3.75V6z" clip-rule="evenodd" />
                 </svg>
              </span>
              <span class="rounded-full transition-colors duration-300 hover:bg-blue-500 px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 transition-colors duration-300 hover:text-white text-gray-600 h-6">
                    <path d="M12.75 12.75a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM7.5 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM8.25 17.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM9.75 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM10.5 17.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM12 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM12.75 17.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM14.25 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM15 17.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM16.5 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM15 12.75a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM16.5 13.5a.75.75 0 100-1.5.75.75 0 000 1.5z" />
                    <path fill-rule="evenodd" d="M6.75 2.25A.75.75 0 017.5 3v1.5h9V3A.75.75 0 0118 3v1.5h.75a3 3 0 013 3v11.25a3 3 0 01-3 3H5.25a3 3 0 01-3-3V7.5a3 3 0 013-3H6V3a.75.75 0 01.75-.75zm13.5 9a1.5 1.5 0 00-1.5-1.5H5.25a1.5 1.5 0 00-1.5 1.5v7.5a1.5 1.5 0 001.5 1.5h13.5a1.5 1.5 0 001.5-1.5v-7.5z" clip-rule="evenodd" />
                 </svg>
              </span>
              <span class="rounded-full transition-colors duration-300 hover:bg-blue-500 px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 transition-colors duration-300 hover:text-white text-gray-600 h-6">
                    <path fill-rule="evenodd" d="M5.25 2.25a3 3 0 00-3 3v4.318a3 3 0 00.879 2.121l9.58 9.581c.92.92 2.39 1.186 3.548.428a18.849 18.849 0 005.441-5.44c.758-1.16.492-2.629-.428-3.548l-9.58-9.581a3 3 0 00-2.122-.879H5.25zM6.375 7.5a1.125 1.125 0 100-2.25 1.125 1.125 0 000 2.25z" clip-rule="evenodd" />
                 </svg>
              </span>
           </div>
        </div>
        <div class="w-[1000px] grid grid-cols-1 rounded-2xl bg-gray-100 pb-4 ">
           <div class="mt-2 mr-6 ml-6">
              <div class="flex justify-between">
                 <div class="flex gap-6">
                  <span class="rounded-full bg-white px-2 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6 text-gray-600">
                       <path fill-rule="evenodd" d="M11.03 3.97a.75.75 0 010 1.06l-6.22 6.22H21a.75.75 0 010 1.5H4.81l6.22 6.22a.75.75 0 11-1.06 1.06l-7.5-7.5a.75.75 0 010-1.06l7.5-7.5a.75.75 0 011.06 0z" clip-rule="evenodd" />
                    </svg>
                 </span>
                 <h3 class="font-bold text-gray-600 text-xl font-base">Weekly Dev Sprint Planning,
               </h3>
               <p class="font-bold text-gray-600 text-xs mt-2 font-base">3, June, 2023</p> 
                 <button class="bg-blue-500 text-sm px-6 py-2 rounded-full text-white font-base">Bi-weekly</button>
                 </div>
                 <span class="rounded-full bg-white px-2 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 text-[#dd4650] h-6">
                       <path fill-rule="evenodd" d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12zm6-2.438c0-.724.588-1.312 1.313-1.312h4.874c.725 0 1.313.588 1.313 1.313v4.874c0 .725-.588 1.313-1.313 1.313H9.564a1.312 1.312 0 01-1.313-1.313V9.564z" clip-rule="evenodd" />
                    </svg>
                 </span>
              </div>
              <div class="flex mt-4 justify-between">
                 <div class="flex gap-4">
                  <span class="rounded-full flex gap-2 bg-white px-4 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 text-gray-600 h-6">
                       <path d="M4.5 6.375a4.125 4.125 0 118.25 0 4.125 4.125 0 01-8.25 0zM14.25 8.625a3.375 3.375 0 116.75 0 3.375 3.375 0 01-6.75 0zM1.5 19.125a7.125 7.125 0 0114.25 0v.003l-.001.119a.75.75 0 01-.363.63 13.067 13.067 0 01-6.761 1.873c-2.472 0-4.786-.684-6.76-1.873a.75.75 0 01-.364-.63l-.001-.122zM17.25 19.128l-.001.144a2.25 2.25 0 01-.233.96 10.088 10.088 0 005.06-1.01.75.75 0 00.42-.643 4.875 4.875 0 00-6.957-4.611 8.586 8.586 0 011.71 5.157v.003z" />
                    </svg>
                    32
                 </span>
                 <button class="bg-teal-500 text-white text-sm font-base inline-flex rounded-full px-4 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 text-white h-5">
                       <path fill-rule="evenodd" d="M12 3.75a.75.75 0 01.75.75v6.75h6.75a.75.75 0 010 1.5h-6.75v6.75a.75.75 0 01-1.5 0v-6.75H4.5a.75.75 0 010-1.5h6.75V4.5a.75.75 0 01.75-.75z" clip-rule="evenodd" />
                    </svg>
                    Add People
                 </button>
                 </div>
                 <div class="flex gap-4 cursor-pointer">
                  <span class="rounded-full text-gray-600 flex gap-2 bg-white px-4 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
  <path d="M15 3.75H9v16.5h6V3.75zM16.5 20.25h3.375c1.035 0 1.875-.84 1.875-1.875V5.625c0-1.036-.84-1.875-1.875-1.875H16.5v16.5zM4.125 3.75H7.5v16.5H4.125a1.875 1.875 0 01-1.875-1.875V5.625c0-1.036.84-1.875 1.875-1.875z" />
</svg>

                    
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
  <path d="M5.625 3.75a2.625 2.625 0 100 5.25h12.75a2.625 2.625 0 000-5.25H5.625zM3.75 11.25a.75.75 0 000 1.5h16.5a.75.75 0 000-1.5H3.75zM3 15.75a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75a.75.75 0 01-.75-.75zM3.75 18.75a.75.75 0 000 1.5h16.5a.75.75 0 000-1.5H3.75z" />
</svg>
<span class="bg-blue-500 rounded-full px-0.5 py-0.5">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5 text-white">
  <path fill-rule="evenodd" d="M1.5 7.125c0-1.036.84-1.875 1.875-1.875h6c1.036 0 1.875.84 1.875 1.875v3.75c0 1.036-.84 1.875-1.875 1.875h-6A1.875 1.875 0 011.5 10.875v-3.75zm12 1.5c0-1.036.84-1.875 1.875-1.875h5.25c1.035 0 1.875.84 1.875 1.875v8.25c0 1.035-.84 1.875-1.875 1.875h-5.25a1.875 1.875 0 01-1.875-1.875v-8.25zM3 16.125c0-1.036.84-1.875 1.875-1.875h5.25c1.036 0 1.875.84 1.875 1.875v2.25c0 1.035-.84 1.875-1.875 1.875h-5.25A1.875 1.875 0 013 18.375v-2.25z" clip-rule="evenodd" />
</svg>
</span>

                 </span>
                 
                 </div>
              </div>
           </div>
           <div class="ml-6 mr-6 mt-2 h-96 bg-cover rounded-lg" :style="{ backgroundImage: `url(${require('@/assets/' + 'premium_photo-1661687442808-02951e1e3ac3.avif')})` }">
           <div class="flex justify-end items-end gap-4 mt-4 mr-4">
            <span class="rounded-full bg-white px-3 py-3">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 text-emerald-500 h-6">
  <path fill-rule="evenodd" d="M16.098 2.598a3.75 3.75 0 113.622 6.275l-1.72.46V12a.75.75 0 01-.22.53l-.75.75a.75.75 0 01-1.06 0l-.97-.97-7.94 7.94a2.56 2.56 0 01-1.81.75 1.06 1.06 0 00-.75.31l-.97.97a.75.75 0 01-1.06 0l-.75-.75a.75.75 0 010-1.06l.97-.97a1.06 1.06 0 00.31-.75c0-.68.27-1.33.75-1.81L11.69 9l-.97-.97a.75.75 0 010-1.06l.75-.75A.75.75 0 0112 6h2.666l.461-1.72c.165-.617.49-1.2.971-1.682zm-3.348 7.463L4.81 18a1.06 1.06 0 00-.31.75c0 .318-.06.63-.172.922a2.56 2.56 0 01.922-.172c.281 0 .551-.112.75-.31l7.94-7.94-1.19-1.19z" clip-rule="evenodd" />
</svg>

              </span>
              <span class="rounded-full bg-blue-500 px-3 py-3">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6  text-white h-6">
                    <path d="M8.25 4.5a3.75 3.75 0 117.5 0v8.25a3.75 3.75 0 11-7.5 0V4.5z" />
                    <path d="M6 10.5a.75.75 0 01.75.75v1.5a5.25 5.25 0 1010.5 0v-1.5a.75.75 0 011.5 0v1.5a6.751 6.751 0 01-6 6.709v2.291h3a.75.75 0 010 1.5h-7.5a.75.75 0 010-1.5h3v-2.291a6.751 6.751 0 01-6-6.709v-1.5A.75.75 0 016 10.5z" />
                 </svg>
              </span>
           </div>
           <div class="mt-64">
  <span class="bg-gray-600 bg-opacity-50 text-sm ml-4 px-4 py-2 font-base rounded-full text-white inline-flex gap-2">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
  <path fill-rule="evenodd" d="M7.5 6a4.5 4.5 0 119 0 4.5 4.5 0 01-9 0zM3.751 20.105a8.25 8.25 0 0116.498 0 .75.75 0 01-.437.695A18.683 18.683 0 0112 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 01-.437-.695z" clip-rule="evenodd" />
</svg>

    Jamie Aiko</span>
</div>
          </div>
           <div class="grid grid-cols-3 gap-x-4 mr-6 ml-6 mt-2">
              <div class="bg-cover rounded-xl h-40" :style="{ backgroundImage: `url(${require('@/assets/' + 'premium_photo-1665203507319-18b26812088a.avif')})` }">
                <div class="flex justify-between  gap-4 mt-2 mr-4 ml-4">
                  <span class="rounded-full bg-blue-500 px-2 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-white">
  <path d="M10.5 1.875a1.125 1.125 0 012.25 0v8.219c.517.162 1.02.382 1.5.659V3.375a1.125 1.125 0 012.25 0v10.937a4.505 4.505 0 00-3.25 2.373 8.963 8.963 0 014-.935A.75.75 0 0018 15v-2.266a3.368 3.368 0 01.988-2.37 1.125 1.125 0 011.591 1.59 1.118 1.118 0 00-.329.79v3.006h-.005a6 6 0 01-1.752 4.007l-1.736 1.736a6 6 0 01-4.242 1.757H10.5a7.5 7.5 0 01-7.5-7.5V6.375a1.125 1.125 0 012.25 0v5.519c.46-.452.965-.832 1.5-1.141V3.375a1.125 1.125 0 012.25 0v6.526c.495-.1.997-.151 1.5-.151V1.875z" />
</svg>

              </span>
              <span class="rounded-full bg-white px-2 py-2">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4  text-gray-600 h-4">
                    <path d="M8.25 4.5a3.75 3.75 0 117.5 0v8.25a3.75 3.75 0 11-7.5 0V4.5z" />
                    <path d="M6 10.5a.75.75 0 01.75.75v1.5a5.25 5.25 0 1010.5 0v-1.5a.75.75 0 011.5 0v1.5a6.751 6.751 0 01-6 6.709v2.291h3a.75.75 0 010 1.5h-7.5a.75.75 0 010-1.5h3v-2.291a6.751 6.751 0 01-6-6.709v-1.5A.75.75 0 016 10.5z" />
                 </svg>
              </span>
           </div>
           <div class="mt-20">
  <span class="bg-gray-600 bg-opacity-50 text-sm ml-4 px-4 py-1 font-base rounded-full text-white inline-flex gap-2">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4">
  <path fill-rule="evenodd" d="M7.5 6a4.5 4.5 0 119 0 4.5 4.5 0 01-9 0zM3.751 20.105a8.25 8.25 0 0116.498 0 .75.75 0 01-.437.695A18.683 18.683 0 0112 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 01-.437-.695z" clip-rule="evenodd" />
</svg>

    Aizula</span>
</div>
              </div>
              <div class="bg-cover rounded-xl h-40"  :style="{ backgroundImage: `url(${require('@/assets/' + '41.png')})` }">
                <div class="flex justify-between  gap-4 mt-2 mr-4 ml-4">
                  <span class="rounded-full invisible bg-blue-500 px-2 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-white">
  <path d="M10.5 1.875a1.125 1.125 0 012.25 0v8.219c.517.162 1.02.382 1.5.659V3.375a1.125 1.125 0 012.25 0v10.937a4.505 4.505 0 00-3.25 2.373 8.963 8.963 0 014-.935A.75.75 0 0018 15v-2.266a3.368 3.368 0 01.988-2.37 1.125 1.125 0 011.591 1.59 1.118 1.118 0 00-.329.79v3.006h-.005a6 6 0 01-1.752 4.007l-1.736 1.736a6 6 0 01-4.242 1.757H10.5a7.5 7.5 0 01-7.5-7.5V6.375a1.125 1.125 0 012.25 0v5.519c.46-.452.965-.832 1.5-1.141V3.375a1.125 1.125 0 012.25 0v6.526c.495-.1.997-.151 1.5-.151V1.875z" />
</svg>

              </span>
              <span class="rounded-full bg-white px-2 py-2">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4  text-gray-600 h-4">
                    <path d="M8.25 4.5a3.75 3.75 0 117.5 0v8.25a3.75 3.75 0 11-7.5 0V4.5z" />
                    <path d="M6 10.5a.75.75 0 01.75.75v1.5a5.25 5.25 0 1010.5 0v-1.5a.75.75 0 011.5 0v1.5a6.751 6.751 0 01-6 6.709v2.291h3a.75.75 0 010 1.5h-7.5a.75.75 0 010-1.5h3v-2.291a6.751 6.751 0 01-6-6.709v-1.5A.75.75 0 016 10.5z" />
                 </svg>
              </span>
              
           </div>

<div class="mt-20">
  <span class="bg-gray-600 bg-opacity-50 text-sm ml-4 px-4 py-1 font-base rounded-full text-white inline-flex gap-2">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4">
  <path fill-rule="evenodd" d="M7.5 6a4.5 4.5 0 119 0 4.5 4.5 0 01-9 0zM3.751 20.105a8.25 8.25 0 0116.498 0 .75.75 0 01-.437.695A18.683 18.683 0 0112 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 01-.437-.695z" clip-rule="evenodd" />
</svg>

    Nick</span>
</div>
              </div>
              <div class="bg-cover rounded-xl h-40"  :style="{ backgroundImage: `url(${require('@/assets/' + 'premium_photo-1661726660137-61b182d93809.avif')})` }">
                <div class="flex justify-between  gap-4 mt-2 mr-4 ml-4">
                  <span class="rounded-full invisible bg-blue-500 px-2 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4 text-white">
  <path d="M10.5 1.875a1.125 1.125 0 012.25 0v8.219c.517.162 1.02.382 1.5.659V3.375a1.125 1.125 0 012.25 0v10.937a4.505 4.505 0 00-3.25 2.373 8.963 8.963 0 014-.935A.75.75 0 0018 15v-2.266a3.368 3.368 0 01.988-2.37 1.125 1.125 0 011.591 1.59 1.118 1.118 0 00-.329.79v3.006h-.005a6 6 0 01-1.752 4.007l-1.736 1.736a6 6 0 01-4.242 1.757H10.5a7.5 7.5 0 01-7.5-7.5V6.375a1.125 1.125 0 012.25 0v5.519c.46-.452.965-.832 1.5-1.141V3.375a1.125 1.125 0 012.25 0v6.526c.495-.1.997-.151 1.5-.151V1.875z" />
</svg>

              </span>
              <span class="rounded-full bg-white px-2 py-2">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4  text-gray-600 h-4">
                    <path d="M8.25 4.5a3.75 3.75 0 117.5 0v8.25a3.75 3.75 0 11-7.5 0V4.5z" />
                    <path d="M6 10.5a.75.75 0 01.75.75v1.5a5.25 5.25 0 1010.5 0v-1.5a.75.75 0 011.5 0v1.5a6.751 6.751 0 01-6 6.709v2.291h3a.75.75 0 010 1.5h-7.5a.75.75 0 010-1.5h3v-2.291a6.751 6.751 0 01-6-6.709v-1.5A.75.75 0 016 10.5z" />
                 </svg>
              </span>
           </div>
           <div class="mt-20">
  <span class="bg-gray-600 bg-opacity-50 text-sm ml-4 px-4 py-1 font-base rounded-full text-white inline-flex gap-2">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-4 h-4">
  <path fill-rule="evenodd" d="M7.5 6a4.5 4.5 0 119 0 4.5 4.5 0 01-9 0zM3.751 20.105a8.25 8.25 0 0116.498 0 .75.75 0 01-.437.695A18.683 18.683 0 0112 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 01-.437-.695z" clip-rule="evenodd" />
</svg>

    Zoe</span>
</div>
              </div>
           </div>
           <div class="cursor-pointer font-base flex gap-4 justify-center items-center mt-1">
              <span class="rounded-full bg-white px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 text-gray-600 h-6">
                    <path d="M4.5 6.375a4.125 4.125 0 118.25 0 4.125 4.125 0 01-8.25 0zM14.25 8.625a3.375 3.375 0 116.75 0 3.375 3.375 0 01-6.75 0zM1.5 19.125a7.125 7.125 0 0114.25 0v.003l-.001.119a.75.75 0 01-.363.63 13.067 13.067 0 01-6.761 1.873c-2.472 0-4.786-.684-6.76-1.873a.75.75 0 01-.364-.63l-.001-.122zM17.25 19.128l-.001.144a2.25 2.25 0 01-.233.96 10.088 10.088 0 005.06-1.01.75.75 0 00.42-.643 4.875 4.875 0 00-6.957-4.611 8.586 8.586 0 011.71 5.157v.003z" />
                 </svg>
              </span>
              <span class="rounded-full bg-white px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6  text-gray-600 h-6">
                    <path fill-rule="evenodd" d="M15 3.75a.75.75 0 01.75-.75h4.5a.75.75 0 01.75.75v4.5a.75.75 0 01-1.5 0V5.56l-3.97 3.97a.75.75 0 11-1.06-1.06l3.97-3.97h-2.69a.75.75 0 01-.75-.75zm-12 0A.75.75 0 013.75 3h4.5a.75.75 0 010 1.5H5.56l3.97 3.97a.75.75 0 01-1.06 1.06L4.5 5.56v2.69a.75.75 0 01-1.5 0v-4.5zm11.47 11.78a.75.75 0 111.06-1.06l3.97 3.97v-2.69a.75.75 0 011.5 0v4.5a.75.75 0 01-.75.75h-4.5a.75.75 0 010-1.5h2.69l-3.97-3.97zm-4.94-1.06a.75.75 0 010 1.06L5.56 19.5h2.69a.75.75 0 010 1.5h-4.5a.75.75 0 01-.75-.75v-4.5a.75.75 0 011.5 0v2.69l3.97-3.97a.75.75 0 011.06 0z" clip-rule="evenodd" />
                 </svg>
              </span>
              <span class="rounded-full bg-white px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6  text-gray-600 h-6">
                    <path d="M8.25 4.5a3.75 3.75 0 117.5 0v8.25a3.75 3.75 0 11-7.5 0V4.5z" />
                    <path d="M6 10.5a.75.75 0 01.75.75v1.5a5.25 5.25 0 1010.5 0v-1.5a.75.75 0 011.5 0v1.5a6.751 6.751 0 01-6 6.709v2.291h3a.75.75 0 010 1.5h-7.5a.75.75 0 010-1.5h3v-2.291a6.751 6.751 0 01-6-6.709v-1.5A.75.75 0 016 10.5z" />
                 </svg>
              </span>
              <button class="bg-[#dd4650] text-sm rounded-full px-6 py-2 text-white" >
              End Meeting</button>
              <span class="rounded-full bg-white px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6  text-gray-600 h-6">
                    <path d="M3.53 2.47a.75.75 0 00-1.06 1.06l18 18a.75.75 0 101.06-1.06l-18-18zM22.5 17.69c0 .471-.202.86-.504 1.124l-4.746-4.746V7.939l2.69-2.689c.944-.945 2.56-.276 2.56 1.06v11.38zM15.75 7.5v5.068L7.682 4.5h5.068a3 3 0 013 3zM1.5 7.5c0-.782.3-1.494.79-2.028l12.846 12.846A2.995 2.995 0 0112.75 19.5H4.5a3 3 0 01-3-3v-9z" />
                 </svg>
              </span>
              <span class="rounded-full bg-white px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6  text-gray-600 h-6">
                    <path fill-rule="evenodd" d="M2.25 5.25a3 3 0 013-3h13.5a3 3 0 013 3V15a3 3 0 01-3 3h-3v.257c0 .597.237 1.17.659 1.591l.621.622a.75.75 0 01-.53 1.28h-9a.75.75 0 01-.53-1.28l.621-.622a2.25 2.25 0 00.659-1.59V18h-3a3 3 0 01-3-3V5.25zm1.5 0v7.5a1.5 1.5 0 001.5 1.5h13.5a1.5 1.5 0 001.5-1.5v-7.5a1.5 1.5 0 00-1.5-1.5H5.25a1.5 1.5 0 00-1.5 1.5z" clip-rule="evenodd" />
                 </svg>
              </span>
              <span class="rounded-full bg-white px-3 py-3">
                 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6  text-gray-600 h-6">
                    <path fill-rule="evenodd" d="M4.5 12a1.5 1.5 0 113 0 1.5 1.5 0 01-3 0zm6 0a1.5 1.5 0 113 0 1.5 1.5 0 01-3 0zm6 0a1.5 1.5 0 113 0 1.5 1.5 0 01-3 0z" clip-rule="evenodd" />
                 </svg>
              </span>
           </div>
        </div>
        <div class="bg-white ">
          <div class="flex gap-40">
            <h3 class="text-gray-900 font-bold text-xl font-base" >Participants</h3>
            <p class="text-gray-600 mt-2 text-xs font-base" >View all</p>
          </div>

         <div class="mt-4 flex flex-col gap-y-4 font-base">
          <div class="bg-gray-100 h-12 rounded-full flex justify-between">
            <div class="flex gap-4">
              <img class="w-10 h-10 mt-1 ml-2 rounded-full object-cover" src="../assets/brooke-cagle-oTweoxMKdkA-unsplash.jpg" alt="">
              <p class="text-gray-600 text-sm mt-3">Brooke</p>
            </div>

            <div class="flex gap-4 mr-6 mt-3 cursor-pointer text-gray-400">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
  <path d="M8.25 4.5a3.75 3.75 0 117.5 0v8.25a3.75 3.75 0 11-7.5 0V4.5z" />
  <path d="M6 10.5a.75.75 0 01.75.75v1.5a5.25 5.25 0 1010.5 0v-1.5a.75.75 0 011.5 0v1.5a6.751 6.751 0 01-6 6.709v2.291h3a.75.75 0 010 1.5h-7.5a.75.75 0 010-1.5h3v-2.291a6.751 6.751 0 01-6-6.709v-1.5A.75.75 0 016 10.5z" />
</svg>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
  <path d="M3.53 2.47a.75.75 0 00-1.06 1.06l18 18a.75.75 0 101.06-1.06l-18-18zM22.5 17.69c0 .471-.202.86-.504 1.124l-4.746-4.746V7.939l2.69-2.689c.944-.945 2.56-.276 2.56 1.06v11.38zM15.75 7.5v5.068L7.682 4.5h5.068a3 3 0 013 3zM1.5 7.5c0-.782.3-1.494.79-2.028l12.846 12.846A2.995 2.995 0 0112.75 19.5H4.5a3 3 0 01-3-3v-9z" />
</svg>

            </div>
          </div>
          <div class="h-12 rounded-full flex justify-between">
            <div class="flex gap-4">
              <img class="w-10 h-10 mt-1 ml-2 rounded-full object-cover" src="../assets/WhatsApp Image 2023-04-02 at 19.44.10.jpeg" alt="">
              <p class="text-gray-600 text-sm mt-3">Nick</p>
            </div>
            
            <div class="flex gap-4 mr-6 mt-3 cursor-pointer text-gray-400">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
  <path d="M8.25 4.5a3.75 3.75 0 117.5 0v8.25a3.75 3.75 0 11-7.5 0V4.5z" />
  <path d="M6 10.5a.75.75 0 01.75.75v1.5a5.25 5.25 0 1010.5 0v-1.5a.75.75 0 011.5 0v1.5a6.751 6.751 0 01-6 6.709v2.291h3a.75.75 0 010 1.5h-7.5a.75.75 0 010-1.5h3v-2.291a6.751 6.751 0 01-6-6.709v-1.5A.75.75 0 016 10.5z" />
</svg>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
  <path d="M3.53 2.47a.75.75 0 00-1.06 1.06l18 18a.75.75 0 101.06-1.06l-18-18zM22.5 17.69c0 .471-.202.86-.504 1.124l-4.746-4.746V7.939l2.69-2.689c.944-.945 2.56-.276 2.56 1.06v11.38zM15.75 7.5v5.068L7.682 4.5h5.068a3 3 0 013 3zM1.5 7.5c0-.782.3-1.494.79-2.028l12.846 12.846A2.995 2.995 0 0112.75 19.5H4.5a3 3 0 01-3-3v-9z" />
</svg>

            </div>
          </div>
          <div class="opacity-40 h-12 rounded-full flex justify-between">
            <div class="flex gap-4">
              <img class="w-10 h-10 mt-1 ml-2 rounded-full object-cover" src="../assets/jonas-kakaroto-KIPqvvTOC1s-unsplash.jpg" alt="">
              <p class="text-gray-600 text-sm mt-3">Jonas</p>
            </div>
            
            <div class="flex gap-4 cursor-pointer mr-6 mt-3 text-gray-400">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
  <path d="M8.25 4.5a3.75 3.75 0 117.5 0v8.25a3.75 3.75 0 11-7.5 0V4.5z" />
  <path d="M6 10.5a.75.75 0 01.75.75v1.5a5.25 5.25 0 1010.5 0v-1.5a.75.75 0 011.5 0v1.5a6.751 6.751 0 01-6 6.709v2.291h3a.75.75 0 010 1.5h-7.5a.75.75 0 010-1.5h3v-2.291a6.751 6.751 0 01-6-6.709v-1.5A.75.75 0 016 10.5z" />
</svg>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5">
  <path d="M3.53 2.47a.75.75 0 00-1.06 1.06l18 18a.75.75 0 101.06-1.06l-18-18zM22.5 17.69c0 .471-.202.86-.504 1.124l-4.746-4.746V7.939l2.69-2.689c.944-.945 2.56-.276 2.56 1.06v11.38zM15.75 7.5v5.068L7.682 4.5h5.068a3 3 0 013 3zM1.5 7.5c0-.782.3-1.494.79-2.028l12.846 12.846A2.995 2.995 0 0112.75 19.5H4.5a3 3 0 01-3-3v-9z" />
</svg>

            </div>
          </div>
         </div>
         <div class="flex justify-between font-base mt-4">
            <h3 class="text-gray-900 font-bold text-xl" >Chat</h3>
            <p class="text-gray-600 mt-2 text-xs" >View all</p>
          </div>

          <div class="mt-4 flex font-base flex-col gap-y-4">
          <div>
            <div class="flex gap-4">
              <img class="w-10 h-10 ml-2 rounded-full object-cover" src="../assets/ben-o-bro-C5XyLljkMrY-unsplash.jpg" alt="">
              <p class="text-gray-400 text-xs mt-3">Ben</p>
            </div>
            <div class="ml-12 bg-gray-100 h-12 flex items-center rounded-xl">
                <p class="text-gray-600 text-start text-xs ml-4">Who's the birthday guy?</p>
          </div>
          </div>

          <div>
            <div class="flex gap-4">
              <img class="w-10 h-10 ml-2 rounded-full object-cover" src="../assets/ehsan-ahmadi-vsWy6nchcOs-unsplash.jpg" alt="">
              <p class="text-gray-400 text-xs mt-3">Ahmadi</p>
            </div>
            <div class="ml-12 bg-gray-100 h-12 flex items-center rounded-xl">
                <p class="text-gray-600 text-start text-xs ml-4">I think it's Nick, yes it's him!</p>
          </div>
          </div>
          <div>
            <div class="flex gap-4">
              <img class="w-10 h-10 ml-2 rounded-full object-cover" src="../assets/jonas-kakaroto-KIPqvvTOC1s-unsplash.jpg" alt="">
              <p class="text-gray-400 text-xs mt-3">Jonas</p>
            </div>
            <div class="ml-12 bg-gray-100 h-12 flex items-center rounded-xl">
                <p class="text-gray-600 text-start text-xs ml-4">Let's see what the client has to say :)</p>
          </div>
          </div>
          <div>
            <div class="flex gap-4">
              <img class="w-10 h-10 ml-2 rounded-full object-cover" src="../assets/thought-catalog--v7EOw5SA4I-unsplash.jpg" alt="">
              <p class="text-gray-400 text-xs mt-3">Maya</p>
            </div>
            <div class="ml-12 bg-gray-100 h-12 flex items-center rounded-xl">
                <p class="text-gray-600 text-start text-xs ml-4">Have a lovely weekend team!</p>
          </div>
          </div>
          <div class="relative font-base mt-4">
            <input type="text" class="bg-gray-100 w-full rounded-full py-5 p-12 placeholder:text-xs text-gray-600 text-sm focus:border-blue-500 focus:outline-none focus:ring-blue-500 focus:ring-2" placeholder="Type a message">
           
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6  absolute top-5 cursor-pointer left-0 ml-4 text-yellow-500 h-6">
  <path fill-rule="evenodd" d="M1.5 6a2.25 2.25 0 012.25-2.25h16.5A2.25 2.25 0 0122.5 6v12a2.25 2.25 0 01-2.25 2.25H3.75A2.25 2.25 0 011.5 18V6zM3 16.06V18c0 .414.336.75.75.75h16.5A.75.75 0 0021 18v-1.94l-2.69-2.689a1.5 1.5 0 00-2.12 0l-.88.879.97.97a.75.75 0 11-1.06 1.06l-5.16-5.159a1.5 1.5 0 00-2.12 0L3 16.061zm10.125-7.81a1.125 1.125 0 112.25 0 1.125 1.125 0 01-2.25 0z" clip-rule="evenodd" />
</svg>

            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 absolute top-5  cursor-pointer right-0 mr-4 text-blue-500 h-6">
  <path d="M3.478 2.405a.75.75 0 00-.926.94l2.432 7.905H13.5a.75.75 0 010 1.5H4.984l-2.432 7.905a.75.75 0 00.926.94 60.519 60.519 0 0018.445-8.986.75.75 0 000-1.218A60.517 60.517 0 003.478 2.405z" />
</svg>

          </div>
          </div>


        </div>
     </div>
  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
