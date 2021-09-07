<template>
  <div class='ibook-layout'>
    <Container>
      <Nuxt/>
    </Container>
  </div>
</template>

<style scoped>
.ibook-layout {
  margin-top: 4.313rem;
  display: grid;
  grid-gap: 6.75rem;

  .container {
    padding-bottom: 6.75rem;
  }

  .footer {
    position: absolute;
    bottom: 0;
    left: 0;
  }
}
</style>
<script>
import Container from '@/components/bosons/Container'
export default {
  components: { Container }
}
</script>
