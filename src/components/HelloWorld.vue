<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})
</script>

<template>
<figure class="md:flex bg-gray-100 rounded-xl p-8 md:p-0">
  <img class="w-32 h-32 md:w-48 md:h-auto md:rounded-none rounded-full mx-auto" src="../assets/handsoff.jpeg" alt="" width="384" height="512">
  <div class="pt-6 md:p-8 text-center md:text-left space-y-4">
    <blockquote>
      <p class="text-lg font-semibold">
        {{msg}}
      </p>
    </blockquote>
    <figcaption class="font-medium">
      <div class="text-cyan-600">
        A marketplace where NFT meets the real world
      </div>
      <div class="text-gray-500">
        Launch day - TBA
      </div>
    </figcaption>
    <div>
      <input type="text" placeholder="Sign up with your email today!" class="px-5 py-2 rounded-full">
      <button type="submit" class="ml-5 border-double border-4 border-light-blue-500 rounded-full"><p class="mx-2">sign up</p></button>
    </div>
  </div>
</figure>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
