<template>
  <div class="home">
    <Carousel />
    <div class="container home__offering">
      <div class="row">
        <div class="col-md-4 home_border">
          <h3 class="home__offeringTitle">
            We are Offering the Best Estate Deals
          </h3>
        </div>
        <div class="col-md-8">
          <p>
            Quisque diam lorem interdum vitaapibus ac scelerisque vitae pede. Donec eget tellus non erat lacinia fertum. Donec in velit vel ipsum auctovinar. Proin umcorper urna et felisstibulum iaculis lacinia est. Proin dictum elem entum velit fusce euismod. Aenean commodo ligula eget dolor. Aenean massa. Lorem ipsum dolor sit amet, consec tetuer adipis elit, aliquam eget nibh etlibura. Lorem ipsum dolor sitamet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et.
          </p>
        </div>
      </div>
    </div>
    <Features :data="featureData"/>
  </div>
</template>

<script>
  import { featureData } from '../data/data.features'
// @ is an alias to /src
  import Carousel from '../components/Carousel.vue'
  import Features from '../components/Features.vue'

  export default {
    name: 'Home',
    components: {
      Carousel,
      Features,
    },
    data (){
      return {
        featureData: featureData,
      }
    },
  }
</script>
