<template>
  <div class="col">
    <h3 class="footer__title">For clients</h3>
    <ul class="footer__list footer__list_capitalize">
      <li v-for="({name, path}, i) in footerMenuClient" :key="i">
        <!-- <a href="#" class="footer__link">{{ menu.name }}</a> -->
        <router-link class="footer__link" :to="path">
          {{ name }}
        </router-link>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    props:{
      footerMenuClient: {
        type: Array,
        required: true
      }
    }
  }
</script>