<template>
  <div class='about-template'>
    <PageTitle text="O que é " strong="iBook"/>
    <Presentation/>
  </div>
</template>

<script>
import PageTitle from '@/components/atoms/PageTitle'
import Presentation from '~/components/organisms/Presentation'
export default {
  name: 'AboutTemplate',
  components: { Presentation, PageTitle }
}
</script>

<style scoped>
.about-template {
  display: grid;
  grid-gap: 4rem;
}
</style>
