<template>
  <div class="w-full bg-green-500 py-4 px-5 shadow flex justify-between items-center">
    <h1 class="text-white font-extrabold">Navbar Apps</h1>
    <ul class="text-white font-semibold flex gap-2">
      <router-link to="/">
        <li>Home</li>
      </router-link>
      <router-link to="/about">
        <li>About</li>
      </router-link>
    </ul>
  </div>
  <router-view />
</template>
