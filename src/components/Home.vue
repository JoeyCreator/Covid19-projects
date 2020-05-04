<template>
  <main>
    <h1>Home</h1>
    <p>Covid-19TrackerQC</p>
    <div class="mt-10 p-4 bg-red-600 rounded-lg shadow-md text-white text-left">
      <strong>
        <i class="fas fa-exclamation-triangle pr-1"></i> Attention
      </strong>
      <p class="mt-1">
        For the most up to date information regarding COVID-19 in Canada, please consult
        <a
          class="border-b border-dotted"
          href="https://www.who.int/health-topics/coronavirus#tab=tab_1"
        >World Health Organization</a>. This site should not be used for life saving information - instead, rather, a source for numbers and statistics.
      </p>
    </div>
    <iframe
      src="https://experience.arcgis.com/experience/4ab8757241cc4d3fab81c8f86a501ce9"
      height="550"
      width="100%"
    ></iframe>
    <div class="pb-4">
      <h4 class="text-xs">
        Developed by Joey Cadieux &middot;
        <a
          class="text-blue-600"
          href="mailto:joey@tech-center.com"
        >Contact Me</a> &middot;
        <a class="text-blue-600" href="https://forms.gle/LoWSvqCgXwYKHLpKA">Found an issue?</a>
      </h4>
    </div>
  </main>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style scoped>
main {
  padding: 100px;
}
</style>