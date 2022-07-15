<template>
  <div class="blog-wrapper">

    <div class="blog-container container">

      <div>
        <h2>Our Blog</h2>
      </div>

      <div>
        <a href="#">Read all articles</a>
      </div>

    </div>

    <BlogArticlesComponent />

  </div>
</template>

<script>
import BlogArticlesComponent from './BlogArticlesComponent.vue';
export default {
    components: { BlogArticlesComponent }
}
</script>

<style lang="scss" scoped>

.blog-wrapper{

  .blog-container{

    display: flex;
    justify-content: space-between;
    align-items: center;

    height: 56px;

    margin-bottom: 40px;

    h2{
      height: 56px;
      width: 820px;
      color: #293E59;
      font-family: Butler;
      font-size: 48px;
      font-weight: bold;
      letter-spacing: -0.3px;
      line-height: 56px;
    }

    a{
      text-decoration: underline;
    }

  }

}

</style>