<template>
  <div class="profile">  
    <nav-bar><slot slot="center">我的</slot></nav-bar>
    
  </div>
</template>

<script>
import NavBar from '../navbar/NavBar'
export default {
  name: 'Profile',
  components: { 
     NavBar
  }
}
</script>

<style>


</style>
