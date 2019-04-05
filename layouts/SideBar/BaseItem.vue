<template>
  <li class="mr-3 flex-1">
    <nuxt-link
      :to="href"
      :class="itemColor"
      class="block py-1 md:py-3 pl-1 align-middle text-white no-underline hover:text-white border-b-2 border-grey-darkest"
    >
      <i :class="icon" class="fas pr-0 md:pr-3"></i
      ><span
        class="pb-1 md:pb-0 text-xs md:text-base text-grey-dark md:text-grey-light block md:inline-block"
        >{{ name }}</span
      >
    </nuxt-link>
  </li>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      default: ''
    },
    icon: {
      type: String,
      default: ''
    },
    color: {
      type: String,
      default: ''
    },
    href: {
      type: String,
      default: '#'
    }
  },
  computed: {
    itemColor() {
      return `hover:border-${this.color}`;
    }
  }
};
</script>
