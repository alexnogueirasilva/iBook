<template>
  <div class='ibook-layout'>
    <Header/>
    <Container>
      <Nuxt/>
    </Container>
    <Footer/>
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
<script lang='ts'>
import Vue from 'vue'
import Container from '~/components/bosons/Container'
import Header from '~/components/organisms/Header'
import Footer from '~/components/organisms/Footer'
export default Vue.extend({
  components: { Footer, Header, Container }
})
</script>
