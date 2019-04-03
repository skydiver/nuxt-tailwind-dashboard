<template>
  <nav
    class="bg-black pt-2 md:pt-1 pb-1 px-1 mt-0 h-auto fixed w-full z-20 pin-t"
  >
    <div class="flex flex-wrap items-center">
      <div
        class="flex flex-shrink md:w-1/3 justify-center md:justify-start text-white"
      >
        <a class="no-underline" href="#">
          <span
            class="text-xl pl-2 text-grey-lighter antialiased font-bold subpixel-antialiased"
            >nuxt-tailwind-dashboard</span
          >
        </a>
      </div>

      <div
        class="flex flex-1 md:w-1/3 justify-center md:justify-start text-white px-2"
      >
        <SearchBar />
      </div>

      <div
        class="flex w-full pt-2 content-center justify-between md:w-1/3 md:justify-end"
      >
        <ul
          class="list-reset flex justify-between flex-1 md:flex-none items-center"
        >
          <li class="flex-1 md:flex-none md:mr-3">
            <a class="inline-block py-2 px-4 text-white no-underline" href="#"
              >Active</a
            >
          </li>
          <li class="flex-1 md:flex-none md:mr-3">
            <a
              class="inline-block text-grey-dark no-underline hover:text-grey-lighter hover:text-underline py-2 px-4"
              href="#"
              >link</a
            >
          </li>
          <li class="flex-1 md:flex-none md:mr-3">
            <UserMenu />
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import SearchBar from '~/layouts/Nav/SearchBar';
import UserMenu from '~/layouts/Nav/UserMenu';

export default {
  components: {
    SearchBar,
    UserMenu
  }
};
</script>

<style scoped></style>
