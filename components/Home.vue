<template>
  <section class="py-12 bg-gray-10 md:py-24">
    <div
      class="grid max-w-screen-xl px-6 mx-auto lg:px-8 xl:px-4 md:grid-cols-4 xl:grid-cols-5 gap-x-12 lg:gap-x-20"
    >
      <div class="self-center order-2 col-span-2 mt-12 md:order-1 md:mt-0">
        <div
          class="inline-flex items-center justify-center w-12 h-12 p-3 mb-6 text-center text-green-400 bg-white rounded-full shadow-md"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-6 h-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"
            />
          </svg>
        </div>
        <h1
          class="mb-2 text-3xl font-bold text-gray-800 md:text-4xl lg:text-5xl md:mb-4 lg:mb-8"
        >
          A simple link but a powerfull tool for
          <span
            class="text-transparent from-green-400 bg-gradient-to-r to-purple-500 bg-clip-text"
            >Youturbers.|</span
          >
        </h1>
        <p class="mb-6 text-lg text-gray-600 xl:text-xl lg:mb-8 xl:mb-10">
          Our tool allows you to seamlessly track your oudience with single and
          easy to remember yet powerful links and provide your customers a
          unique tailored experience.
        </p>
        <form class="flex mb-2" action="">
          <input
            type="text"
            placeholder="https://www.youtube.com/watch?v=6457bpRtA80"
            class="flex-1 p-4 leading-none transition duration-500 border border-gray-100 rounded-l-lg shadow-md focus:outline-none focus:border-green-400"
          />
          <button
            type="submit"
            class="inline-block px-4 py-2.5 font-semibold text-white transition duration-500 bg-green-400 shadow-md rounded-r-lg hover:bg-green-500"
          >
            <!-- Try now -->
            Shorten
          </button>
        </form>
        <p class="mb-8 text-xs text-gray-500">
          <!-- By clicking shorten, you agree to Rebrandly's
          <a href="" class="underline">Term of Uses</a> and
          <a href="" class="underline">Privacy</a>. -->
          Use it, it's free...Fast - Secure - Long Term Link
        </p>
        <div
          class="flex justify-center space-x-2 md:justify-start md:space-x-4"
        >
          <div
            class="inline-flex items-center justify-center w-1/2 px-5 py-3 font-semibold text-center text-white transition duration-500 bg-green-400 rounded-lg shadow-md cursor-pointer hover:bg-green-500"
          >
            Get Started
            <svg
              class="w-4 h-4 ml-1"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </div>
          <div
            class="inline-flex items-center justify-center w-1/2 px-5 py-3 font-semibold text-center text-gray-800 transition duration-500 bg-white border border-gray-100 rounded-lg shadow-md cursor-pointer hover:bg-gray-100"
          >
            Learn more
            <svg
              class="w-4 h-4 ml-1"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"
              ></path>
            </svg>
          </div>
        </div>
      </div>
      <div class="flex order-1 col-span-2 md:order-2 xl:col-span-3">
        <img src="@/assets/images/share_link.svg" alt="Link shortener" />
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>

<style scoped></style>
