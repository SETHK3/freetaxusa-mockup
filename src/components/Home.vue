<template>
  <div class="home">
    <div class="navbar-wrapper">
      <div class="navbar-section">
        <img
          src="./../assets/freetax-logo.svg"
          alt="FreeTaxUSA Logo"
          class="logo"
        />
        <div class="nav-links">
          <a href="#">Pricing and Products</a>
          <a href="#">Support</a>
          <a href="#">Prior Year</a>
          <a href="#">After You File</a>
        </div>
        <button class="sign-in">
          <font-awesome-icon :icon="['fas', 'lock']" />Sign In
        </button>
      </div>

      <div class="notification-bar">
        <p>
          Looking to prepare your <a href="#">2023</a> tax return?
          <a href="#">Sign in to 2023</a>
        </p>
      </div>
    </div>

    <div class="main-content">
      <img
        src="./../assets/capitol-building.svg"
        alt="Capitol Building"
        class="main-image"
      />
      <h1>Free federal return for everyone</h1>
      <p>Get a head start on your 2024 taxes</p>
      <button class="start-button">Start 2024 return</button>

      <div class="pricing-info">
        <span>Federal $0</span> <span>State $14.99</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  setup() {
    return {};
  },
};
</script>

<style lang="scss">
.home {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: Lexend, sans-serif;
  color: #272d41;
  width: 100%;
  box-sizing: border-box;
}

.navbar-wrapper {
  position: fixed;
  width: 100%;

  .navbar-section {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    padding: 1rem 1rem;
    background-color: white;
    border-bottom: 1px solid gray;
    box-sizing: border-box;
  }

  .logo {
    height: 30px;
  }

  .nav-links {
    display: flex;
    gap: 1.5rem;
    font-size: 1.2rem;

    a {
      text-decoration: none;
      color: #272d41;
    }
  }

  .sign-in {
    background-color: #0950c5;
    color: #fff;
    border: none;
    border-radius: 1px;
    padding: 0.5rem 1rem;
    font-family: Lexend, sans-serif;
    font-size: 1.2rem;
    cursor: pointer;
  }
}

.notification-bar {
  width: 100%;
  text-align: center;
  border-bottom: 1px solid gray;

  a {
    text-decoration: none;
  }
}

.main-content {
  text-align: center;
  padding: 2rem 1rem;
  background-color: white;
  margin-top: 7rem;

  .main-image {
    width: 400px;
    margin: 1rem 0;
  }

  h1 {
    font-size: 5rem;
    margin-top: -1rem;
  }

  p {
    font-size: 2.2rem;
    margin-top: -3rem;
  }

  .start-button {
    background-color: #0950c5;
    color: #fff;
    border: none;
    padding: 2rem 2rem;
    cursor: pointer;
    margin: 1rem 0;
    font-family: Lexend, sans-serif;
    font-size: 1.3rem;
  }

  .pricing-info {
    font-size: 1.1rem;
    display: flex;
    gap: 2.5rem;
    justify-content: center;
  }
}
</style>
