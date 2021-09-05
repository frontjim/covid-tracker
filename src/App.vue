<template>
  <Header />
  <router-view class="m-10"/>
  <Footer class="m-10"/>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'
export default {
  components: {
    Header,
    Footer
  }
  
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');
* {
  font-family: 'Poppins', sans-serif;
}
</style>