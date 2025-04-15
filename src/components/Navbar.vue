<script>
export default {
  name: 'Navbar',
  data() {
    return {
      isMenuOpen: false
    }
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen
    }
  }
}
</script>

<template>
  <nav class="bg-black text-white w-full">

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">

      <div class="flex justify-between h-16 md:h-20">

        <div class="flex items-center">
          <img src="/logo-light.png.png" alt="GRAVITY TEAM" class="h-6 md:h-8" />
        </div>


        <div class="hidden md:flex items-center space-x-4 lg:space-x-8">
          <a href="#" class="hover:text-yellow-400 transition duration-300 text-sm lg:text-base">ABOUT US</a>

          <div class="relative">
            <a href="#" class="flex items-center hover:text-yellow-400 transition duration-300 text-sm lg:text-base">
              OUR SERVICES
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24"
                stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </a>
          </div>

          <a href="#" class="hover:text-yellow-400 transition duration-300 text-sm lg:text-base">WORK WITH US</a>
          <a href="#" class="hover:text-yellow-400 transition duration-300 text-sm lg:text-base">BLOG</a>


          <button
            class="bg-transparent border border-yellow-400 rounded-full px-4 py-1 lg:px-6 lg:py-2 flex items-center hover:bg-yellow-400 hover:text-black transition duration-300 text-sm lg:text-base ml-4">
            <span class="mr-2 h-2 w-2 bg-yellow-400 rounded-full"></span>
            GET IN TOUCH
          </button>
        </div>


        <div class="md:hidden flex items-center">
          <button @click="toggleMenu" class="focus:outline-none" type="button">
            <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path v-if="!isMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16" />
              <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
            </svg>
          </button>
        </div>
      </div>
    </div>


    <div v-if="isMenuOpen" class="md:hidden">
      <div class="px-2 pt-2 pb-3 space-y-1 border-t border-gray-800">
        <a href="#" class="block px-3 py-2 hover:text-yellow-400 transition duration-300">ABOUT US</a>
        <a href="#" class="block px-3 py-2 hover:text-yellow-400 transition duration-300">OUR SERVICES</a>
        <a href="#" class="block px-3 py-2 hover:text-yellow-400 transition duration-300">WORK WITH US</a>
        <a href="#" class="block px-3 py-2 hover:text-yellow-400 transition duration-300">BLOG</a>


        <div class="px-3 py-3">
          <button
            class="w-full bg-transparent border border-yellow-400 rounded-full px-6 py-2 flex items-center justify-center hover:bg-yellow-400 hover:text-black transition duration-300">
            <span class="mr-2 h-2 w-2 bg-yellow-400 rounded-full"></span>
            GET IN TOUCH
          </button>
        </div>
      </div>
    </div>
  </nav>
</template>