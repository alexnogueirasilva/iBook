<template>
  <div class='releases'></div>
</template>

<script>
export default {
  name: 'Releases'
}
</script>

<style lang='scss' scoped>
.releases {
  display: grid;
  grid-gap: 1.3rem;

  h2 {
    font-size: 1.375rem;
    font-weight: 500;
    color: color(dark, darkest);
  }
}
</style>
