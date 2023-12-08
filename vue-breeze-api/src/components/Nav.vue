<script setup>

</script>

<template>
  <!-- component -->
<header>
  <nav>
    <div class="">
      <div class="flex justify-between h-16 px-10 shadow items-center">
        <div class="flex items-center space-x-8">
          <h1 class="text-xl lg:text-2xl font-bold cursor-pointer">Tailwind</h1>
          <div class="hidden md:flex justify-around space-x-4">
            <router-link :to="{name: 'Home'}" class="hover:text-indigo-600 text-gray-700">Home</router-link>
            <a href="#" class="hover:text-indigo-600 text-gray-700">About</a>
            <a href="#" class="hover:text-indigo-600 text-gray-700">Service</a>
            <a href="#" class="hover:text-indigo-600 text-gray-700">Contact</a>
          </div>
        </div>
        <div class="flex space-x-4 items-center">
          <router-link :to="{name: 'Login'}" class="text-gray-800 text-sm">LOGIN</router-link>
          <router-link :to="{name: 'Register'}" class="bg-indigo-600 px-4 py-2 rounded text-white hover:bg-indigo-500 text-sm">REGISTRATION</router-link>
        </div>
      </div>
    </div>
  </nav>
</header>
</template>