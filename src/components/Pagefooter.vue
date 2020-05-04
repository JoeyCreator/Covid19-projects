<template>
  <div class="bg-black">
    <div class="px-5 md:px-0 py-5 container mx-auto flex sm:justify-between justify-start">
      <div class="w-1/2">
        <p
          class="text-sm text-white"
        >Copyright &copy; {{ getYear() }} Tracking Covid-19, LLC. All rights reserved.</p>
      </div>
      <div class="w-1/2"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Pagefooter",
  methods: {
    getYear() {
      return new Date().getFullYear();
    }
  }
};
</script>

<style>
nav a {
  text-decoration: none;
}
</style>