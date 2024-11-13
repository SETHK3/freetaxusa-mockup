<template>
  <div class="home">
    <nav class="navbar">
      <img src="./logo.png" alt="FreeTaxUSA Logo" class="logo" />
      <ul class="nav-links">
        <li><a href="#">Pricing and Products</a></li>
        <li><a href="#">Support</a></li>
        <li><a href="#">Prior Year</a></li>
        <li><a href="#">After You File</a></li>
      </ul>
      <button class="sign-in">Sign In</button>
    </nav>

    <div class="notification-bar">
      <p>
        Looking to prepare your <a href="#">2023</a> tax return?
        <a href="#">Sign in to 2023</a>
      </p>
    </div>

    <main class="main-content">
      <img src="./main-image.png" alt="Capitol Building" class="main-image" />
      <h1>Free federal return for everyone</h1>
      <p>Get a head start on your 2024 taxes</p>
      <button class="start-button">Start 2024 return</button>

      <div class="pricing-info">
        <span>Federal $0</span> <span>State $14.99</span>
      </div>
    </main>
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

<style lang="scss"></style>
