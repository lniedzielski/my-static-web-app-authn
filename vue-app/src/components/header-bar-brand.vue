<script>
export default {
  name: 'HeaderBarBrand',
};
</script>

<template>
  <div class="navbar-brand">
    <a
      class="navbar-item"
      href="https://vuejs.org/"
      target="_blank"
      rel="noopener noreferrer"
    >
    </a>
    <router-link to="/" class="navbar-item nav-home">
      <span class="brand-first">MY</span>
      <span class="brand-second">SHOPPING</span>
      <span class="brand-third">LIST</span>
    </router-link>
  </div>
</template>
