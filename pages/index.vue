<template>
  <div class="box">
    <HomeTemplate/>
  </div>
</template>

<script lang='ts'>
import Vue from 'vue'
import HomeTemplate from '~/components/templates/HomeTemplate.vue'

 export default Vue.extend({
   components: { HomeTemplate },
   layout: 'ibook'
 })
</script>
