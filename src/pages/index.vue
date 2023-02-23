<script setup lang="ts">

</script>

<template>
  <div class="flex items-center flex-col w-full h-100vh text-gray-700 dark:text-gray-200">
    <button class="my-2 icon-btn !outline-none text-20px" @click="toggleDark()">
      <div i="carbon-sun dark:carbon-moon" />
    </button>
    <div class="flex shrink-0">
      <Preview />
      <div class="w-360px h-360px ml-20px p-10px rounded-4px shadow-iu dark:shadow-iu-dark">
        edit
      </div>
    </div>
    <CodeBox />
  </div>
</template>

<style scoped lang="scss">

</style>
