<script setup>
const searchBarInputPlaceholder = 'Search for a movie, tv show, person...';
const searchButtonText = 'Search';
</script>

<template>
  <div class="w-full">
    <input class="shadow appearance-none rounded-3xl w-full h-[46px] bg-white py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" type="text" :placeholder="searchBarInputPlaceholder">
    <button class="w-[100px] h-[46px] rounded-3xl absolute right-0 focus:outline-none bg-gradient-to-r from-[rgba(30,213,169,1)] to-[rgba(1,180,228,1)] hover:border-none hover:text-black transition duration-500">{{ searchButtonText }}</button>
  </div>
</template>
