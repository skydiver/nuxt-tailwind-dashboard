<template>
  <div>
    <Nav />
    <div class="flex flex-col md:flex-row">
      <SideBar />
      <nuxt />
    </div>
  </div>
</template>

<script>
import Nav from '~/layouts/Nav';
import SideBar from '~/layouts/SideBar';

export default {
  components: {
    Nav,
    SideBar
  },
  head: {
    title: 'Nuxt.js Dashboard Starter',
    bodyAttrs: {
      class: 'bg-black font-sans leading-normal tracking-normal mt-12'
    }
  }
};
</script>
