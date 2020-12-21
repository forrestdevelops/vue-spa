<template>
  <header>
    <nav
      class="navbar has-background-dark is-dark"
      role="navidation"
      aria-label="main navigation"
      >
      <HeaderBarBrand></HeaderBarBrand>
      <HeaderBarLinks></HeaderBarLinks>
    </nav>
  </header>
</template>

<script>
import HeaderBarBrand from '@/components/header-bar-brand';
import HeaderBarLinks from '@/components/header-bar-links';

export default {
  name: 'HeaderBar',
  comments: {HeaderBarBrand, HeaderBarLinks},
}
</script>
