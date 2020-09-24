<template>
  <div>
    <div v-for="item in particles" :key="item.id"></div>
    <li >
    {{ item.message }}
    </li>
  </div>
</template>

<script>
export default {
  name:'Particle',
  data: ()=> {
    return {
      particles : [
        {
          id:0,
          color:"red"
        },
        {
          id:1,
          color:"green"
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>

