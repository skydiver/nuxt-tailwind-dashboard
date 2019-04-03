<template>
  <div>
    <Nav />
    <nuxt />
  </div>
</template>

<script>
import Nav from '~/layouts/Nav';

export default {
  components: {
    Nav
  },
  head: {
    title: 'Nuxt.js Dashboard Starter',
    bodyAttrs: {
      class: 'bg-black font-sans leading-normal tracking-normal mt-12'
    }
  }
};
</script>
