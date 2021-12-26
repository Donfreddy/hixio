<template>
  <header class="bg-gray-10 ">
    <div
      class="flex justify-between max-w-screen-xl px-6 py-4 mx-auto lg:px-8 xl:px-4 lg:py-6"
    >
      <nuxt-link to="/" class="text-3xl font-semibold">
        Hix.io
      </nuxt-link>
      <nav class="flex items-center space-x-4">
        <nuxt-link
          class="flex items-center space-x-1 font-medium transition duration-500 hover:text-green-400"
          to="/"
        >
          Login
        </nuxt-link>
        <nuxt-link to="/">
          <div
            class="inline-block px-4 py-2 font-semibold text-white transition duration-500 bg-green-400 rounded-lg shadow-md hover:bg-green-500"
          >
            <!-- Get Started -->
            Sign up
          </div>
        </nuxt-link>
      </nav>
    </div>
  </header>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>
