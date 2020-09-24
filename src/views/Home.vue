<template>
  <div class="home">
    <div class="home--content">
      <!-- <router-link to="/chatbot">About</router-link> -->
      <Ogun />
      <h3>Hey je suis Ogun ! on fait connaissance ?</h3>
      <h5>Tape sur ogun pour commencer</h5>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Ogun from '@/components/Ogun'

export default {
  name: 'Home',
  components: {
    Ogun
  },
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap');
  .home{
    width: 100%;
    font-family: 'Roboto', sans-serif;
    height: 100vh;
    display:flex;
    justify-content: center;
    align-items: center;
    background-color: #2B303E;
    .home--content{
      width: 80%;
      height: 70%;
      display:flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      h3{
        color: white;
        text-align: center;
        margin:10px;
      }
      h5{
        font-weight: 400;
        color: #A0A0A0
      }
    }
  }
</style>

