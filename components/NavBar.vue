<template>
    <nav class="fixed top-4 left-4 z-50">
      <div class="relative">
        <!-- Main Nav Button -->
        <div 
          @click="toggleDropdown"
          @mouseenter="isHovered = true"
          @mouseleave="isHovered = false"
          class="flex items-center bg-white rounded-full shadow-lg hover:shadow-xl transition-shadow duration-300 cursor-pointer"
        >
          <!-- Logo Section -->
          <div class="h-12 w-12 flex items-center justify-center bg-white rounded-full overflow-hidden">
            <img 
              src="/images/saint-normal.png" 
              alt="Logo" 
              class="h-12 w-12 object-contain"
            />
          </div>
          
          <!-- Text Section -->
          <div class="px-4 pr-6">
            <span class="text-gray-700 font-medium text-lg tracking-wide">Youne</span>
          </div>
        </div>
  
        <!-- Dropdown Menu -->
        <Transition
          enter-active-class="transition duration-200 ease-out"
          enter-from-class="transform opacity-0 -translate-y-2"
          enter-to-class="transform opacity-100 translate-y-0"
          leave-active-class="transition duration-200 ease-in"
          leave-from-class="transform opacity-100 translate-y-0"
          leave-to-class="transform opacity-0 -translate-y-2"
        >
          <div 
            v-show="isDropdownOpen || isHovered"
            @mouseenter="isHovered = true"
            @mouseleave="isHovered = false"
            class="absolute top-full left-0 mt-2 py-2 w-48 bg-white/90 backdrop-blur-sm rounded-xl shadow-lg"
          >
            <!-- Home Link -->
            <NuxtLink 
              to="/"
              class="block px-4 py-2 text-gray-700 transition-colors duration-200 font-medium hover:text-pink-400"
            >
              Home
            </NuxtLink>
            
            <!-- Login Link -->
            <NuxtLink 
              to="/login"
              class="block px-4 py-2 text-gray-700 transition-colors duration-200 font-medium hover:text-pink-400"
            >
              Login
            </NuxtLink>
  
            <!-- About Link -->
            <NuxtLink 
              to="/about"
              class="block px-4 py-2 text-gray-700 transition-colors duration-200 font-medium hover:text-pink-400"
            >
              About
            </NuxtLink>
          </div>
        </Transition>
      </div>
    </nav>
  </template>
  
  <script setup>
  const isHovered = ref(false)
  const isDropdownOpen = ref(false)
  
  const toggleDropdown = () => {
    isDropdownOpen.value = !isDropdownOpen.value
  }
  
  onMounted(() => {
    document.addEventListener('click', (e) => {
      const nav = e.target.closest('nav')
      if (!nav) {
        isDropdownOpen.value = false
      }
    })
  })
  </script>