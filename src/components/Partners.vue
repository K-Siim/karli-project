<template>
    <section class="relative bg-black bg-opacity-95 text-white py-12 md:py-20 overflow-hidden">
      
      <div class="absolute bottom-0 left-0 w-80 h-80 bg-purple-600 opacity-20 blur-3xl rounded-full"></div>
      
      <div class="max-w-6xl mx-auto px-4 relative z-10">
        
        <div class="relative">
          
          <div class="hidden md:block absolute left-0 top-1/2 transform -translate-y-1/2 opacity-80">
            <div class="flex flex-col space-y-8">
              <img src="/near.png.png" alt="Near" class="w-16 lg:w-20" />
              <img src="/solana.png.png" alt="Solana" class="w-16 lg:w-20" />
              <img src="/solana.png.png" alt="Solana" class="w-16 lg:w-20" /> 
            </div>
          </div>
          
          <div class="flex flex-col md:flex-row md:items-center">
            
            <div class="md:w-1/3 mb-8 md:mb-0 text-center md:text-left md:pl-24 lg:pl-32">
              <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-white">
                Our Partners<br>& Friends
              </h2>
              
              
              <div class="flex justify-center md:hidden mt-6 space-x-4">
                <img src="/near.png.png" alt="Near" class="w-12 h-auto" />
                <img src="/solana.png.png" alt="Solana" class="w-12 h-auto" />
                <img src="/solana.png.png" alt="Solana" class="w-12 h-auto" />
              </div>
            </div>
            
            
            <div class="md:w-2/3">
              <img 
                src="/div copy 2.png" 
                alt="Our Partners" 
                class="max-w-full h-auto w-full"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'PartnersSection'
  }
  </script>
  
  <style scoped>
  
  section {
    background: linear-gradient(to bottom right, rgba(25, 25, 35, 0.95), rgba(15, 15, 25, 0.98));
  }
  </style>