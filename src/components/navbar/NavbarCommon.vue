<template>
  <div class="w-full bg-green-400 py-3 px-5 shadow flex justify-between items-center">
    <h1 class="text-white font-extrabold">{{ name }}</h1>
    <ul class="text-white font-semibold flex gap-2">
      <li>Home</li>
      <li>About</li>
    </ul>
  </div>
</template>

<script>
export default {
  props: {
    name: String
  }
}
</script>
