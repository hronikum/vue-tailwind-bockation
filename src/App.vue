<template>
  <div id="app"class=" min-h-screen bg-gray-200 antialiased">
    <header class=" flex justify-between bg-gray-900 px-4 py-3 text-gray-500 font-bold">Workation
      <button>
        <svg class="h-6 w-6 fill-current text-gray-500" height="24px" id="Layer_1" style="enable-background:new 0 0 24 24;" version="1.1" viewBox="0 0 32 32" width="24px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path d="M4,10h24c1.104,0,2-0.896,2-2s-0.896-2-2-2H4C2.896,6,2,6.896,2,8S2.896,10,4,10z M28,14H4c-1.104,0-2,0.896-2,2  s0.896,2,2,2h24c1.104,0,2-0.896,2-2S29.104,14,28,14z M28,22H4c-1.104,0-2,0.896-2,2s0.896,2,2,2h24c1.104,0,2-0.896,2-2  S29.104,22,28,22z"/></svg>
    </button>
    </header>
    <section class="flex justify-between bg-gray-800  px-4 py-3">
      <div class="relative">
        <div class="absolute inset-y-0 left-0 flex items-center pl-3">
          <svg class="h-6 w-6 fill-current text-gray-600" width="24" height="24" xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" clip-rule="evenodd"><path d="M15.853 16.56c-1.683 1.517-3.911 2.44-6.353 2.44-5.243 0-9.5-4.257-9.5-9.5s4.257-9.5 9.5-9.5 9.5 4.257 9.5 9.5c0 2.442-.923 4.67-2.44 6.353l7.44 7.44-.707.707-7.44-7.44zm-6.353-15.56c4.691 0 8.5 3.809 8.5 8.5s-3.809 8.5-8.5 8.5-8.5-3.809-8.5-8.5 3.809-8.5 8.5-8.5z"/></svg>
        </div>
        <input class="bg-gray-900 focus:outline-non focus:bg-white focus:text-gray-900 text-white rounded-lg px-10 pr-4 py-2" placeholder="Search by keywords">
      </div>   
      <button class="inline-flex items-center bg-gray-700 hover:bg-gray-600 focus:outline-non focus:shadow-outline focus:bg-gray-600 rounded-lg shadow pl-4 pr-4">
        <svg class="h-6 w-6 fill-current text-gray-500" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M13 6h-13v-4h13v4zm0 4h-13v4h13v-4zm0 8h-13v4h13v-4zm3-8l4 5.075 4-5.075h-8z"/></svg>
        <span class="ml-1 text-white font-medium">Filters</span>
      </button>
    </section>
    <main class="px-4 py-6">
      <h3 class="text-gray-900 text-xl">Los Angeles</h3>
      <p class="text-gray-600">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur, asperiores?</p>
      <div class="mt-6">
        <div>
          <div>
            <img class="rounded-lg shadow-md h-64" src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="">
          </div>
          <div class="relative px-4 -mt-16">
            <div class=" bg-white rounded-lg shadow-lg px-4 py-4">
              <div class="flex">
                <span class="inline-block px-2 py-1 leading-none bg-teal-200 text-teal-800 rounded-full font-semibold uppercase tracking-wide text-xs">Plus</span>
                <div class="ml-2 text-xs text-gray-600 font-semibold uppercase tracking-wide ">
                  3 beds &bull; 2 baths
                </div>
              </div>
              <h4 class="mt-1 text-gray-900 font-semibold text-lg">Modern home in city center</h4>
              <div class="mt-1">
                <span class=" text-gray-900">$1,400</span><span class="ml-1 text-sm text-gray-600">/wk</span>
              </div>
              <div class="mt-2 flex items-center text-sm text-gray-600 ">
                <svg class="h-4 w-4 fill-current text-teal-500" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
                <svg class="h-4 w-4 fill-current text-teal-500" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
                <svg class="h-4 w-4 fill-current text-teal-500" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
                <svg class="h-4 w-4 fill-current text-teal-500" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
                <svg class="h-4 w-4 fill-current text-teal-500" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M12 .587l3.668 7.568 8.332 1.151-6.064 5.828 1.48 8.279-7.416-3.967-7.417 3.967 1.481-8.279-6.064-5.828 8.332-1.151z"/></svg>
                
                <span class="ml-2">34 reviews</span>
              </div>
            </div>
          </div>
          
          
        </div>
      </div>
    </main>

  </div>
</template>
<script>
export default {
  name: 'app',
  components: {}
}

</script>
<style src="./assets/css/tailwind.css">
</style>
