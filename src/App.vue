<template>
  <!-- <h1 ref="here">
    Here Comes The Life.
  </h1> -->
  <Here ref="here" />
</template>

 <script>
import Here from '~/components/Here'
export default {
  components:{
    Here
  },
  // created(){
  //   console.log(this.$refs.here)
  // },
  mounted(){
    // const h1El = document.querySelector('h1')
    // const h1El = document.querySelector('#here')
    // console.log(h1El.textContent)
    console.log(this.$refs.here.$refs.alive)
  }
}
</script>

