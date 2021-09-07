<template>
  <footer class='footer'>
    <container>
      <Logo/>
      <p>Copyright &copy; {{ currentYear }} iBook</p>
    </container>
  </footer>
</template>

<script lang='ts'>
import Container from '@/components/bosons/Container'
import Logo from '@/components/atoms/Logo'
export default {
  components: { Logo, Container },
  computed:{
    currentYear(){
      return new Date().getFullYear()
    }
  }
}
</script>

<style lang='scss' scoped>
.footer {
  width: 100%;
  height: 110px;
  background: color('dark', 'darkest');
  .container {
    display: grid;
    height: 100%;
    grid-auto-flow: column;
    justify-content: space-between;
    align-items: center;
    p {
      color: color('light', 'darkest');
    }
  }
}
</style>
