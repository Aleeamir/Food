<template>
  <header class="header" style="background-color: rgb(138, 132, 132);">
    <div class="header-logo">
      <router-link to="/">
        <img src="/src/assets/Images/logo.png" alt="Your Logo Alt Text" />
      </router-link>
    </div>
    <nav class="header-nav">
      <router-link to="/" class="header-nav-link">Home</router-link>
      <router-link to="/about" class="header-nav-link">About</router-link>
      <router-link to="/services" class="header-nav-link">Services</router-link>
      <router-link to="/projects" class="header-nav-link">Projects</router-link>
      <router-link to="/news" class="header-nav-link">News</router-link>
      <router-link to="/shop" class="header-nav-link">Shop</router-link>
      <router-link to="/contact" class="header-nav-link">Contact</router-link>
    </nav>
    <div class="header-cta">
      <router-link to="/cale" class="header-cta-link">Cale</router-link>
      <a href="tel:+980009630" class="header-cta-phone">+98 (000) - 9630</a>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 100;
  box-sizing: border-box;
  overflow: hidden;
}

.header-logo {
  display: flex;
  align-items: center;
}

.header-logo img {
  height: 3rem;
}

.header-nav a {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.header-nav,
.header-cta {
  display: flex;
  align-items: center;
}

.header-nav-link,
.header-cta-link,
.header-cta-phone {
  margin-left: 2rem;
  text-decoration: none;
  color: #333;
  font-size: 1.2rem;
  transition: color 0.2s ease-in-out;
}

.header-nav-link:hover,
.header-cta-link:hover {
  color: #007bff;
}

.header-cta-link {
  margin-left: 0;
  /* margin-right: 20px; */
}

@media (max-width: 768px) {
  .header {
    flex-direction: column;
  }

  .header-logo,
  .header-nav,
  .header-cta {
    margin-bottom: 1rem;
  }

  .header-nav-link,
  .header-cta-link {
    margin-left: 0;
  }
}
</style>
