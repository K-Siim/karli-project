<template>
    <section class="relative bg-black text-white py-16 px-4 md:px-8 lg:px-16">
      <div class="container mx-auto">
        
        <h2 class="text-5xl md:text-6xl lg:text-7xl font-bold text-center mb-12">Contact Us</h2>
        
        <div class="flex flex-col md:flex-row items-center justify-between">
          
          <div class="w-full md:w-1/4 relative">
            <img 
              src="/image1.png" 
              alt="Blue glow"
              class="w-full h-auto max-w-full"
            />
          </div>
          
          
          <div class="w-full md:w-1/2 px-4 md:px-8 text-center my-10 md:my-0">
            <p class="text-lg md:text-xl lg:text-2xl text-white text-center mb-12 max-w-3xl mx-auto leading-relaxed">
              We are always open to discuss new value-adding partnerships. Do reach
              out if you are an exchange or a project looking for liquidity; an algorithmic
              trader or a software developer looking to improve the markets with us or
              just have a great idea you can't wait to share with us!
            </p>
            
            
            <a 
              href="#contact-form" 
              class="inline-block px-12 py-4 font-medium rounded-md text-white uppercase tracking-wider text-lg bg-gradient-to-r hover:opacity-90 transition-opacity duration-300"
              style="background-image: linear-gradient(to right, #665DCD, #5FA4E6, #D2AB67);"
            >
              GET IN TOUCH
            </a>
          </div>
          
          
          <div class="w-full md:w-1/4 relative">
            <img 
              src="/div22.png" 
              alt="Contact frame"
              class="w-full h-auto max-w-full"
            />
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'ContactComponent',
  }
  </script>