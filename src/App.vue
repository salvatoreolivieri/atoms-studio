<template>
  <div id="app">

    <HeaderComponent />

    <HeroSectionComponent />

    <ServiceSectionComponent />

    <BlogSectionComponent />

    <PlatformComponent />

    <NesletterComponent />

    <FooterComponent />
    
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import HeroSectionComponent from './components/HeroSectionComponent.vue';
import ServiceSectionComponent from './components/ServiceSectionComponent.vue';
import BlogSectionComponent from './components/BlogSectionComponent.vue';
import PlatformComponent from './components/PlatformComponent.vue';
import NesletterComponent from './components/NesletterComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    HeroSectionComponent,
    ServiceSectionComponent,
    BlogSectionComponent,
    PlatformComponent,
    NesletterComponent,
    FooterComponent
  }
}
</script>

<style lang="scss">

@import './assets/style/global';
@import './assets/style/var';

@font-face {
  font-family: "Fira Sans";
  src: local("Fira Sans"),
   url(./assets/font/Fira_Sans/FiraSans-Regular.ttf) format("truetype");
}

</style>