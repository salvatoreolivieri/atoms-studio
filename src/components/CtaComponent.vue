<template>

  <div class="cta-container container">

    <div class="newsletter-wrapper">

      <NewsletterLightComponent />

    </div>

    <div class="background-image"></div>

  </div>

</template>

<script>

import NewsletterLightComponent from './NewsletterLightComponent.vue';

export default {
    name: "CtaComponent",
    components: { NewsletterLightComponent }
}

</script>

<style lang="scss" scoped>

.cta-container{
  margin-top: 140px;
  height: 350px;


  display: flex;
  align-items: center;
  justify-content: space-between;


  background-image: url('../assets/img/Group 2.jpg');
  background-size: contain ;
  background-repeat: no-repeat ;

  .newsletter-wrapper{

    margin-left: 111px;

  }

}

</style>