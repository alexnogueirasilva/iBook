<template>
  <div class='box'>
    <HomeTemplate />
  </div>
</template>

<script lang='ts'>
import Vue from 'vue'
import HomeTemplate from '~/components/templates/HomeTemplate.vue'
import { books } from '@/store'

export default Vue.extend({
  components: { HomeTemplate },
  layout: 'ibook',
  asyncData(){
    console.log(books.books)
  }
})
</script>
