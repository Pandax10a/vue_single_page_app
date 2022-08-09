<template>
  <div>
    <myheader/>
    <mybody/>
    <myfooter/>
  </div>
</template>

<script>


import myheader from '@/components/header.vue'

export default {

  components: {
    myheader,
    mybody,
    myfooter,
  },
  
}
import mybody from '@/components/body.vue'
import myfooter from '@/components/footer.vue'


</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
