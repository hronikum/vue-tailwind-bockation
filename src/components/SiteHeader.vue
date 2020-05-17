<template>
  <header class="bg-gray-900 text-gray-500">
    <div class="flex justify-between px-4 py-3 font-bold">
      <span class=" text-2xl">Workation</span>
      <div class="flex">
        <button @click="toggle" type="button" class="px-2 text-gray-500 hover:text-white focus:outline-none focus:text-white">
            <span v-if="isOpen" class="font-bold">X</span>
            <svg v-else class="h-6 w-6 fill-current " height="24px" id="Layer_1" style="enable-background:new 0 0 24 24;" version="1.1" viewBox="0 0 32 32" width="24px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <path d="M4,10h24c1.104,0,2-0.896,2-2s-0.896-2-2-2H4C2.896,6,2,6.896,2,8S2.896,10,4,10z M28,14H4c-1.104,0-2,0.896-2,2  s0.896,2,2,2h24c1.104,0,2-0.896,2-2S29.104,14,28,14z M28,22H4c-1.104,0-2,0.896-2,2s0.896,2,2,2h24c1.104,0,2-0.896,2-2  S29.104,22,28,22z" /></svg>
        </button>
      </div>
    </div>
    <nav v-show="isOpen">
      <div class="px-2 pt-2 pb-5 border-b border-gray-800">
        <a href="#" class="block px-3 py-1 rounded font-semibold text-white hover:bg-gray-800">List your property</a>
        <a href="#" class="mt-1 block px-3 py-1 rounded font-semibold text-white hover:bg-gray-800">Trips</a>
        <a href="#" class="mt-1 block px-3 py-1 rounded font-semibold text-white hover:bg-gray-800">Messages</a>
      </div>
      <div class="px-5 py-5 ">
        <div class="flex items-center">
          <img class="h-10 w-10 object-cover rounded-full border-2 border-gray-600" src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=256&q=80" alt="">
          <span class="ml-4 font-semibold text-gray-200">Isla Schoger</span>
        </div>
        <div class="mt-5">
          <a href="#" class="block text-grey-400 hover:text-white">Account settings</a>
          <a href="#" class="mt-3 block text-grey-400 hover:text-white">Support</a>
          <a href="#" class="mt-3 block text-grey-400 hover:text-white">Sign out</a>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  props: [],
  data() {
    return {
      isOpen: false,
    }
  },
  methods: {
    toggle(){
      this.isOpen = !this.isOpen
    },
  },
}
</script>