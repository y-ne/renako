<template>
    <div class="flex items-center justify-center min-h-screen px-4 py-20">
      <div class="max-w-3xl mx-auto">
        <!-- Main Title -->
        <h1 class="text-4xl font-bold mb-8 text-center opacity-0 animate-slideDown">
          <span class="bg-gradient-to-r from-pink-400 to-blue-400 bg-clip-text text-transparent">
            ./
          </span>
          <span class="text-gray-700">Youne Baldea</span>
        </h1>
  
        <!-- Cards Container -->
        <div class="space-y-4">
          <!-- Introduction Card -->
          <div class="opacity-0 animate-slideUp" style="animation-delay: 400ms;">
            <div class="bg-white/50 backdrop-blur-sm p-8 rounded-2xl shadow-md">
              <h2 class="text-xl font-medium mb-3 text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-blue-400">
                Introduction
              </h2>
              <p class="text-gray-700 leading-relaxed space-y-4">
                <span class="block">
                  Sorry if it little bit boring and bland, but I like this style.
                </span>
                
                <span class="block">
                  Anyway, I am usually known as 
                  <span class="font-medium text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-blue-400">
                    kuu
                  </span>. 
                  I've been doing electronic repair full-time since 2016.
                </span>
                
                <span class="block">
                  In my free time, I like to tinker with Linux-related stuff, networking, or embedded systems in general.
                </span>
                
                <span class="block">
                  As for programming in my hobby projects, I mainly focus on writing firmware and services, given their close relation to electronics.
                </span>
                
                <span class="block">
                  Recently, I've been expanding my knowledge by delving into the field of artificial intelligence.
                </span>
              </p>
            </div>
          </div>
  
          <!-- Position Card -->
          <div class="opacity-0 animate-slideUp" style="animation-delay: 600ms;">
            <div class="bg-white/50 backdrop-blur-sm p-8 rounded-2xl shadow-md">
              <h2 class="text-xl font-medium mb-3 text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-blue-400">
                Position
              </h2>
              <p class="text-gray-700 leading-relaxed">
                Electrical & Embedded System Engineer, Web Developer, Data Engineer
              </p>
            </div>
          </div>
  
          <!-- Arsenal Card -->
          <div class="opacity-0 animate-slideUp" style="animation-delay: 800ms;">
            <div class="bg-white/50 backdrop-blur-sm p-8 rounded-2xl shadow-md">
              <h2 class="text-xl font-medium mb-4 text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-blue-400">
                Arsenal
              </h2>
              <!-- Grid for tech stack -->
              <div class="grid grid-cols-2 md:grid-cols-3 gap-3">
                <!-- C++ -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:c-plusplus" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">C/C++</span>
                  </div>
                </div>
  
                <!-- Rust -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:rust" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">Rust</span>
                  </div>
                </div>
  
                <!-- Go -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:go" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">Go</span>
                  </div>
                </div>
  
                <!-- Python -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:python" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">Python</span>
                  </div>
                </div>
  
                <!-- TypeScript -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:typescript-icon" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">TypeScript</span>
                  </div>
                </div>
  
                <!-- Docker -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:docker-icon" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">Docker</span>
                  </div>
                </div>
  
                <!-- Redis -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:redis" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">Redis</span>
                  </div>
                </div>
  
                <!-- PostgreSQL -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:postgresql" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">Postgres</span>
                  </div>
                </div>
  
                <!-- RabbitMQ -->
                <div class="tech-card group relative flex items-center space-x-3 bg-white/60 p-3 rounded-lg transition-all duration-300 overflow-hidden">
                  <div class="absolute inset-0 w-full h-full translate-x-[-101%] bg-pink-200 group-hover:translate-x-0 transition-transform duration-300"></div>
                  <div class="relative z-10 flex items-center space-x-3">
                    <Icon icon="logos:rabbitmq-icon" class="w-5 h-5" />
                    <span class="text-gray-700 group-hover:text-gray-800 transition-colors duration-300">RabbitMQ</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  import { Icon } from '@iconify/vue'
  </script>
  
  <style scoped>
  @keyframes slideDown {
    0% { 
      opacity: 0;
      transform: translateY(-10px);
    }
    100% { 
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  @keyframes slideUp {
    0% { 
      opacity: 0;
      transform: translateY(10px);
    }
    100% { 
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  .animate-slideDown {
    animation: slideDown 0.8s ease-out forwards;
  }
  
  .animate-slideUp {
    animation: slideUp 0.8s ease-out forwards;
  }
  </style>