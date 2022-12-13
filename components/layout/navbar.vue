<script setup lang="ts">
</script>

<template>
  <div class="navbar relative dark:bg-black">
    <div class="max-w-7xl mx-auto px-4 sm:px-6">
      <div class="flex justify-between  border-b-2 border-gray-100">
        <div class="flex justify-between min-w-full md:min-w-0">
          <div class="">
            <nuxt-link to="/">
              <span class="sr-only">Home</span>
              <img class="h-16 md:h-24 w-auto transition duration-500 scale-50 md:hover:scale-110"
                src="/img/logo_clear_fsj.png" />
            </nuxt-link>
          </div>
        </div>
        <nav class="hidden md:flex justify-between space-x-10 align-bottom mt-14">
          <div class="hidden md:flex space-x-10 align-bottom">
            <nuxt-link to="/articles/overview">
              <span
                class="text-base font-medium text-gray-500 dark:text-gray-200 hover:text-gray-900 dark:hover:text-gray-300 ">
                Articles
              </span>
            </nuxt-link>
          </div>
        </nav>
      </div>
    </div>
  </div>

</template>
