<template>
  <div class="home">
    <MainContainer>
      <h1>Home page 1</h1>
    </MainContainer>
  </div>
</template>

<script>
// @ is an alias to /src
  import MainContainer from '../components/MainContainer.vue'

  export default {
    name: 'Home',
    components: {
      MainContainer,
    }
  }
</script>
