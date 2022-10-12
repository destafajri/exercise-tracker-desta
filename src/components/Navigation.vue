<template>
  <header class="bg-at-light-green text-white">
    <nav class="container py-5 px-4 flex flex-col gap-4 items-center sm:flex-row">
      <div class="flex items-center gap-x-4">
        <img class="w-14" src="../assets/images/dumbbell-light.png" alt="">
        <h1 class="text-lg">Active Tracker</h1>
      </div>
      <ul class="flex flex-1 justify-end gap-x-10">
        <RouterLink class="cursor-pointer" :to="{ name: 'Home' }">Home</RouterLink>
        <RouterLink class="cursor-pointer" :to="{ name: '' }">Create</RouterLink>
        <RouterLink class="cursor-pointer" :to="{ name: '' }">Login</RouterLink>
        <li class="cursor-pointer">Logout</li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  setup() {
    // Get user from store

    // Setup ref to router

    // Logout function

    return {};
  },
};
</script>
