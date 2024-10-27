<template>
  <div class="min-h-screen flex items-center justify-center">
    <!-- Login Card with soft shadow and animation -->
    <div 
      class="w-full max-w-sm p-8 bg-[#fff8f6]/50 backdrop-blur-sm rounded-2xl shadow-[0_8px_30px_rgb(0,0,0,0.08)] 
             transform transition-all duration-300 hover:shadow-[0_8px_30px_rgb(0,0,0,0.12)]
             animate-fadeIn"
    >
      <!-- Header -->
      <h1 
        class="text-3xl font-bold text-[#967969] text-center mb-8
               animate-slideDown"
      >
        Log me in, please!
      </h1>

      <form class="space-y-6">
        <!-- Username Input -->
        <div>
          <input
            type="text"
            placeholder="Username"
            class="w-full px-4 py-3 rounded-xl bg-white border-2 border-transparent 
                   focus:border-[#ddb7ab] transition-all duration-300 outline-none
                   animate-slideRight placeholder-[#c4b0a6]"
          />
        </div>

        <!-- Password Input -->
        <div>
          <input
            type="password"
            placeholder="Password"
            class="w-full px-4 py-3 rounded-xl bg-white border-2 border-transparent 
                   focus:border-[#ddb7ab] transition-all duration-300 outline-none
                   animate-slideLeft placeholder-[#c4b0a6]"
          />
        </div>

        <!-- Login Button with animation -->
        <button
          type="submit"
          class="w-full py-3 px-4 bg-[#8e6f64] text-white font-medium 
                 rounded-xl transition-all duration-300 
                 transform hover:scale-[1.02] hover:bg-[#7d625a] 
                 focus:outline-none active:scale-95
                 animate-slideUp"
        >
          Sign In
        </button>
      </form>
    </div>
  </div>
</template>

<script setup>
// Empty for now since we're focusing on UI
</script>

<style>
/* Custom animations */
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

@keyframes slideDown {
  from { transform: translateY(-20px); opacity: 0; }
  to { transform: translateY(0); opacity: 1; }
}

@keyframes slideRight {
  from { transform: translateX(-20px); opacity: 0; }
  to { transform: translateX(0); opacity: 1; }
}

@keyframes slideLeft {
  from { transform: translateX(20px); opacity: 0; }
  to { transform: translateX(0); opacity: 1; }
}

@keyframes slideUp {
  from { transform: translateY(20px); opacity: 0; }
  to { transform: translateY(0); opacity: 1; }
}

/* Apply animations */
.animate-fadeIn {
  animation: fadeIn 0.5s ease-out;
}

.animate-slideDown {
  animation: slideDown 0.5s ease-out;
}

.animate-slideRight {
  animation: slideRight 0.5s ease-out 0.2s backwards;
}

.animate-slideLeft {
  animation: slideLeft 0.5s ease-out 0.3s backwards;
}

.animate-slideUp {
  animation: slideUp 0.5s ease-out 0.4s backwards;
}
</style>