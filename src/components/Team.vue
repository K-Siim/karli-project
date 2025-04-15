<template>
    <section class="relative bg-black text-white py-16 px-4 md:px-8 lg:px-12">
      <div class="container mx-auto">
        <div class="flex flex-col md:flex-row items-center gap-8">
          
          <div class="w-full md:w-1/2 relative">
            <div class="relative overflow-hidden rounded-lg">
              <img 
                src="/image1.png" 
                alt="Glowing blue background" 
                class="w-full h-auto"
              />
              <div class="absolute inset-0 flex items-center justify-center">
                <h2 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white leading-tight">
                  Join
                  <br />Gravity Team
                </h2>
              </div>
            </div>
          </div>
          
          
          <div class="w-full md:w-1/2">
            <p class="mb-6 text-white">
              Join our community of innovators, problem solvers and owners who apply scientific discovery techniques to make crypto markets a better place for everyone.
            </p>
            
            <p class="mb-8 text-white">
              As we emphasize it in our name – Gravity Team, we are a team. A team of bright, talented people, each masters of their specialty, curious about the world and eager to solve the new exciting cryptocurrency market problems, build cool stuff and have fun whilst doing so!
            </p>
            
            <div class="flex items-center">
              <a href="#learn-more" class="inline-flex items-center text-white border-b border-white pb-1 hover:text-gray-300 transition-colors duration-300">
                Learn more about working with us
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'TeamComponent',
  }
  </script>