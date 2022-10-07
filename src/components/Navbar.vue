<template>
  <nav class="bg-[#22195b] p-5 md:p-8 w-full sticky shadow-lg">
    <div
      class="container mx-auto flex h-full justify-between items-center md:px-3"
    >
      <div>
        <h1 class="text-xl md:text-4xl text-white font-semibold">SoloCode</h1>
      </div>
      <div class="">
        <router-link
          class="text-md md:text-2xl pl-4 text-white font-semibold"
          to="/"
          >Home</router-link
        >
        <router-link
          class="text-2xltext-md md:text-2xl pl-4 text-white font-semibold"
          to="/dashboard"
          >Dashboard</router-link
        >
        <router-link
          class="text-md md:text-2xl pl-4 text-white font-semibold"
          to="/table"
          >Table</router-link
        >
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style></style>
