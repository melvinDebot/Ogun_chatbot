<template>
  <div class="ogun">
    <router-link to="/chatbot">
      <img :src="logo" alt="ogun chatbot"/>
    </router-link>
  </div>
</template>

<script>
import logo from '../assets/logo.svg'
export default {
  name:"Ogun",
  data: ()=> {
    return {
      logo : logo
    }
  }
}
</script>

<style lang="scss" scoped>
  .ogun{
    width: 90%;
    height: auto;
    display:flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 6em
  }
</style>

