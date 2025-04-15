<template>
  <section class="relative bg-black bg-opacity-95 text-white py-16 overflow-hidden">
    
    <div class="absolute bottom-0 left-0 w-80 h-80 bg-purple-600 opacity-20 blur-3xl rounded-full z-0"></div>

    <div class="max-w-7xl mx-auto px-4 relative z-10">
      <div class="flex flex-col md:flex-row items-center justify-between gap-10">

        
        <div class="md:w-1/2 relative flex justify-center items-center min-h-[300px]">
          
          <div class="absolute -top-20 left-[35%] transform -translate-x-1/2">
            <img src="/near.png.png" alt="Near" class="w-10 h-auto" />
          </div>
          <div class="absolute -top-10 left-[40%] transform -translate-x-1/2">
            <img src="/solana.png.png" alt="Solana" class="w-10 h-auto" />
          </div>
          <div class="absolute 0 top-0 left-[30%] transform -translate-x-1/2">
            <img src="/solana.png.png" alt="Solana 2" class="w-10 h-auto" />
          </div>

          
          <div class="text-center md:text-left">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold leading-tight">
              Our<br />
              Partners<br />
              & Friends
            </h2>
          </div>
        </div>

        
        <div class="md:w-1/2 flex justify-center md:justify-end">
          <img 
            src="/div copy 2.png" 
            alt="Partner Logos" 
            class="w-full max-w-[380px] h-auto"
          />
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
