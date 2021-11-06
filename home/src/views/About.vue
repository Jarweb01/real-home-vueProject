<template>
  <MainContainer>
    <h1>This is an about page</h1>
  </MainContainer>
</template>

<script>
// @ is an alias to /src
  import MainContainer from '../components/MainContainer.vue'

  export default {
    name: 'about',
    components: {
      MainContainer,
    }
  }
</script>
