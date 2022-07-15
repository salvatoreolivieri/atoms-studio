<template>

<div class="hero-section-wrapper">

  <!-- Cerchio nello sfondo: -->
  <div class="backgroud-circle"></div>


  <div class="hero-section-container container">

    <!-- Unique Value Proposition: -->
    <div class="unique-selling-position-container">
      <h1>Performance without compromises</h1>

      <p>How we helped Blumarine to conquer new businesses</p>

      <button class="button-without-background">
        Discover
      </button>
    </div>

    <!-- Immagine della ragazza: -->
    <div class="backgroud-hero-image">
      <img src="../assets/img/Blauer Detroit D5_612.jpg" alt="">
    </div>

    <!-- Contenitore Call To Action Newsletter:-->
    <div class="newsletter-cta">

      <div class="newsletter-wrapper">

        <img src="../assets/img/delete.svg" alt="">

        <h3>From our studio</h3>
        <p>Get a weekly email with inspirational contents from <br> Zerogrey.</p>
  
        <form action="">
          
          <input type="email" id="email" placeholder="write your e-mail" required><br>
  
          <input type="checkbox" name="privacy_policy" id="checkbox" required>
          <span>I read and accept the Privacy Policy</span>
    
        </form>

      </div>


    </div>


  </div>

</div>

  
</template>

<script>

export default {
  name:"HeroSectionComponent"
}

</script>

<style lang="scss" scoped>

@import "../assets/style/var";

.hero-section-wrapper{

  width: 100%;
  position: relative;

  overflow: hidden;

  margin-bottom: 120px;

  .backgroud-circle{

      background-color: rgba(128, 199, 229, 0.5);

      width: 880px;
      height: 880px;
      border-radius: 50%;

      position: absolute;
      top: 0;
      right: -150px;

  }

  .hero-section-container{

    position: relative;

    height: 880px;

    .unique-selling-position-container{

      position: absolute;
      z-index: 20;

      top: 170px;
      left: 0;

      h1{

        height: 160px;
        width: 814px;

        color: #293E59;

        font-family: Butler;
        font-size: 72px;
        font-weight: bold;
        letter-spacing: -0.3px;
        line-height: 80px;

      }

      p{

        height: 48px;
        width: 329px;

        color: #9B9B9B;

        font-family: "Fira Sans";
        font-size: 16px;
        letter-spacing: 0;
        line-height: 24px;

        margin: 20px 0;

      }

    }

    .backgroud-hero-image{

      width: 755px;
      height: 566px;

      position: absolute;
      z-index: 10;
      top: 32px;
      right: 127px;

      img{
        width: 100%;
      }

    }

    .newsletter-cta{

      width: 486px;
      height: 294px;

      padding: 40px;

      background-color: #293E59;

      position: absolute;
      z-index: 11;
      bottom: 76px;
      right: -36px;

      .newsletter-wrapper{
        position: relative;

        img{
          position: absolute;
          top: 0;
          right: 0;

          cursor: pointer;
        }

        h3{

          height: 40px;
          width: 225px;

          color: #FFFFFF;

          font-family: Butler;
          font-size: 32px;
          font-weight: bold;
          letter-spacing: -0.3px;
          line-height: 40px;

        }

        p{

          height: 40px;
          width: 390px;

          margin-top: 10px;
          margin-bottom: 30px;

          color: #FFFFFF;

          font-family: "Fira Sans";
          font-size: 14px;
          letter-spacing: 0;
          line-height: 20px;

        }



        #email{

          width: 100%;

          background-color: #293E59;
          color: #CACACA;

          border: none;
          padding: 2px;
          margin-bottom: 12px;

          border-bottom: 1px solid white;

          font-size: 14px;
          letter-spacing: 0;
          line-height: 20px;

          &:focus{
            outline: none;
          }

        }

        #checkbox{
          border: none;
        }

        span{
          display: inline-block;
          margin-left: 5px;

          height: 18px;
          width: 194px;

          color: #FFFFFF;

          font-family: "Fira Sans";
          font-size: 12px;
          letter-spacing: 0;
          line-height: 18px;
        } 


      }


      





    }

  }

}



</style>