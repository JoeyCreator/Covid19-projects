<template>
  <main>
    <h1>LiveStream</h1>
    <p>Tracking Covid-19</p>
    <p>Covid-19TrackerQc is a projects in development</p>
    <iframe
      src="https://covid19canada.maps.arcgis.com/apps/Minimalist/index.html?appid=b3baccb0f30e4516b8e64009b3383f55"
      height="500"
      width="100%"
    ></iframe>
  </main>
</template>

<script>
export default {
  name: "LiveStream"
};
</script>

<style scoped>
main {
  padding: 100px;
}
</style>