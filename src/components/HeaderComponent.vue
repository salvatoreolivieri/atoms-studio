<template>

    <header>

      <!-- Logo: -->
      <div class="logo-container">
        <img src="../assets/img/logo-3.svg" alt="logo">
      </div>


      <!-- Navigazione: -->
      <nav>

        <ul>

          <li>
            <a href="#">Works</a>
          </li>

          <li>
            <a href="#">Services</a>
          </li>

          <li>
            <a href="#">Why Us</a>
          </li>

          <li>
            <button>Let's Talk</button>
          </li>

        </ul>

      </nav>

    </header>

</template>

<script>
export default {
  name:"HeaderComponent",
}

</script>

<style lang="scss" scoped>

header{

  height: 43px;
  max-width: 1316px;

  margin: 20px 56px 20px 68px;

  display: flex;
  justify-content: space-between;
  align-items: center;

  .logo-container{
    width: 196px;

    img{
      width: 100%;
      cursor: pointer;

    }
  }

  nav{

    ul{
      display: flex;
      align-items: center;

      li{
        list-style: none;
        margin-right: 20px;

        a{
          text-decoration: none;

          height: 20px;
          width: 40px;

          font-family: "Fira Sans";
          font-size: 14px;
          font-weight: 500;
          letter-spacing: 0;
          line-height: 20px;

        }

      }

    }

  }

}

</style>