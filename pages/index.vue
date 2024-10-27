<template>
    <div class="flex items-center justify-center min-h-screen px-4">
      <div class="text-center max-w-2xl mx-auto animate-fadeIn">
        <!-- Main greeting -->
        <h1 class="text-4xl md:text-5xl mb-4 animate-slideDown">
          Hi, name's 
          <span class="font-bold bg-gradient-to-r from-pink-400 to-blue-400 bg-clip-text text-transparent">
            Youne
          </span>
        </h1>
        
        <!-- Stylized names with consistent spacing -->
        <p class="text-lg md:text-xl mb-4 animate-slideUp">
          Stylized as 
          <span class="inline-block font-medium text-transparent bg-clip-text bg-gradient-to-r from-pink-400 via-blue-400 to-pink-400 bg-[length:200%] hover:bg-right transition-all duration-500">
            y-ne
          </span>
          <span class="mx-2">or</span>
          <span class="inline-block font-medium text-transparent bg-clip-text bg-gradient-to-r from-blue-400 via-pink-400 to-blue-400 bg-[length:200%] hover:bg-right transition-all duration-500">
            Y姉
          </span>
        </p>
  
        <!-- The Talentless with special styling -->
        <p class="text-lg md:text-xl text-gray-900 animate-slideUp" style="animation-delay: 200ms;">
          An individual who goes by the nickname 
          <span class="relative inline-block group">
            <span class="font-medium text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-blue-400">
              'The Talentless'
            </span>
            <span class="absolute bottom-0 left-0 w-0 h-[2px] bg-gradient-to-r from-pink-400 to-blue-400 group-hover:w-full transition-all duration-300"></span>
          </span>
        </p>
      </div>
    </div>
  </template>