<template>
    <div class="min-h-screen flex items-center justify-center bg-gray-50">
      <div class="max-w-md w-full p-6 bg-white rounded-lg shadow-md">
        <!-- Simple Header -->
        <h1 class="text-2xl font-bold text-center mb-6">Login</h1>
  
        <!-- Simple Form -->
        <form class="space-y-4">
          <!-- Username -->
          <div>
            <input
              type="text"
              placeholder="Username"
              class="w-full p-2 border rounded-md"
            />
          </div>
  
          <!-- Password -->
          <div>
            <input
              type="password"
              placeholder="Password"
              class="w-full p-2 border rounded-md"
            />
          </div>
  
          <!-- Login Button -->
          <button
            type="submit"
            class="w-full bg-blue-500 text-white p-2 rounded-md hover:bg-blue-600"
          >
            Login
          </button>
        </form>
      </div>
    </div>
  </template>
  
  <script setup>
  // Empty for now since we're just doing UI
  </script>