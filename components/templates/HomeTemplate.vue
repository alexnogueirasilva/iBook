<template>
<div class='home-template'>
  <PageTitle text='Bem vindo ao' strong='iBook'/>
  <Releases/>
</div>
</template>

<script>
import PageTitle from '@/components/atoms/PageTitle'
import Releases from '@/components/organisms/Releases'
export default {
  name: 'HomeTemplate',
  components: { Releases, PageTitle }
}
</script>

<style  lang='scss' scoped>
.home-template {
  display: grid;
  grid-gap: 4rem;
}
</style>
