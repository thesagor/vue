<script setup>
defineProps({
  list: {
    type: String
  },
})

</script>

<template>
  <header class="p-4 pb-20">
    <div class="w-full max-w-7xl mx-auto">
      <div class="flex justify-between gap-8 items-center">
        <div>
          <a class=" font-bold text-4xl" href=""><span class="border-b-4 border-black">Lin</span>gare</a>
        </div>
        <div class="flex items-center gap-8">
          <nav class="hidden lg:flex gap-8">
            <a class="hover:underline" href="">Collections</a>
            <a class="hover:underline" href="">Featured products</a>
            <a class="hover:underline" href="">Contact us</a>
          </nav>
          <span class="hidden lg:block">|</span>
          <div class="flex gap-4 text items-center">
            <a href="">
              <i
                  class="flex items-center justify-center bg-black text-white rounded-full w-[35px] h-[35px] bi bi-search"></i>
            </a>
            <a href="">
              <i
                  class="flex items-center justify-center bg-black text-white rounded-full w-[35px] h-[35px] bi bi-bag"></i>
            </a>
            <a class="text-2xl" href="">
              <i
                  class="flex items-center justify-center bg-black text-white rounded-full w-[35px] h-[35px] bi bi-person"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>

</style>