<template>
    <section class="relative bg-black bg-opacity-95 text-white py-16 md:py-24 overflow-hidden">
      <!-- Background gradient effects -->
      <div class="absolute bottom-0 left-0 w-96 h-96 bg-purple-600 opacity-20 blur-3xl rounded-full"></div>
      <div class="absolute top-1/2 right-0 w-96 h-96 bg-purple-600 opacity-20 blur-3xl rounded-full"></div>
      <div class="absolute bottom-1/3 left-1/4 w-64 h-64 bg-blue-500 opacity-10 blur-3xl rounded-full"></div>
      
      <div class="max-w-6xl mx-auto px-4 relative z-10">
        <!-- Main Header -->
        <div class="text-center mb-16">
          <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6 text-white">Crypto Market Making</h2>
          <p class="text-base md:text-lg max-w-2xl mx-auto text-white">
            We are a global crypto liquidity provider and algorithmic market 
            maker. We trade digital assets listed on Centralized Exchanges in 
            over 15 countries worldwide.
          </p>
        </div>
        
        <!-- Market Making for Crypto Projects Section -->
        <div class="grid md:grid-cols-2 gap-12 mb-20 items-center">
          <div class="order-2 md:order-1">
            <h3 class="text-2xl md:text-3xl font-bold mb-4 text-white">Market Making for<br>Crypto Projects</h3>
            
            <h4 class="text-lg md:text-xl font-semibold mb-3 text-white">
              Accelerate your token's journey by boosting its liquidity
            </h4>
            
            <p class="mb-6 text-white">
              We invest in building long-term, sustainable relationships and support our 
              projects in their growth journey with our services, industry expertise and network.
            </p>
            
            <a href="#" class="inline-flex items-center text-white hover:text-gray-300 transition">
              Learn more
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
              </svg>
            </a>
          </div>
          
          <div class="order-1 md:order-2 flex justify-center">
            <img src="/div.png" alt="Market Making Illustration" class="max-w-full h-auto" />
          </div>
        </div>
        
        <!-- Market Making for Crypto Exchanges Section -->
        <div class="grid md:grid-cols-2 gap-12 mb-24 items-center">
          <div class="flex justify-center">
            <img src="/div copy.png" alt="Exchange Trading Interface" class="max-w-full h-auto" />
          </div>
          
          <div>
            <h3 class="text-2xl md:text-3xl font-bold mb-4 text-white">Market Making for<br>Crypto Exchanges</h3>
            
            <h4 class="text-lg md:text-xl font-semibold mb-3 text-white">
              Attract more traders and projects with deep order books & liquidity
            </h4>
            
            <p class="mb-6 text-white">
              Our world-class market making services are proven to help local and emerging exchanges 
              win traders and gain market-leading positions of up to 90% market dominance.
            </p>
            
            <a href="#" class="inline-flex items-center text-white hover:text-gray-300 transition">
              Learn more
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'MarketSection'
  }
  </script>
  
  <style scoped>
  
  section {
    background: linear-gradient(to bottom right, rgba(25, 25, 35, 0.95), rgba(15, 15, 25, 0.98));
  }
  </style>