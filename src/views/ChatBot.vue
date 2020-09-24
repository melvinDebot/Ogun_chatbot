<template>
  <div class="main">
    <iframe
    allow = "microphone;"
    width = "100%"
    height = "100%"
    src = "https://console.dialogflow.com/api-client/demo/embedded/640f170f-62d4-4835-8053-27cb011a703d">
    </iframe>
  </div>
</template>

<style lang="scss" scoped>
  .main{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    @media  (min-width: 700px) {
      iframe{
        width:700px;
        height: 600px;
      }
    }
  }
</style>

