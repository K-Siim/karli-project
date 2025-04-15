<template>
    <footer class="bg-black text-white py-12 px-4 md:px-8 lg:px-16">
      <div class="container mx-auto">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-16">
          
          <div class="mb-8 md:mb-0">
            <h3 class="text-lg font-bold mb-6">GRAVITY TEAM</h3>
            <nav>
              <ul class="space-y-4">
                <li>
                  <a href="/about" class="text-gray-300 hover:text-white transition-colors">About Us</a>
                </li>
                <li>
                  <a href="/work" class="text-gray-300 hover:text-white transition-colors">Work with Us</a>
                </li>
              </ul>
            </nav>
          </div>
          
          
          <div>
            <img 
              src="/logo-light.png.png" 
              alt="Gravity Team Logo" 
              class="h-12 w-auto"
            />
          </div>
        </div>
        
        
        <div class="flex flex-col md:flex-row justify-between items-center pt-8 border-t border-gray-800">
          <div>
            <a href="/terms" class="text-gray-400 hover:text-white transition-colors text-sm">
              Terms of Use & Privacy Policy
            </a>
          </div>
          <div class="mt-4 md:mt-0">
            <p class="text-gray-400 text-sm">©2022 Gravity Team. All Rights Reserved</p>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'FooterComponent',
  }
  </script>