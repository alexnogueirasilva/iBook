<template>
  <AboutTemplate/>
</template>

<script lang='ts'>
import Vue from 'vue'
import AboutTemplate from '@/components/templates/AboutTemplate.vue'
export default Vue.extend({
  name: 'about',
  layout: 'ibook',
  components: { AboutTemplate }
})
</script>
