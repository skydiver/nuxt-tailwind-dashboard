<template>
  <div
    class="bg-black shadow-lg h-16 fixed pin-b mt-12 md:relative md:h-screen z-10 w-full md:w-48"
  >
    <div
      class="md:mt-12 md:w-48 md:fixed md:pin-l md:pin-t content-center md:content-start text-left justify-between"
    >
      <ul
        class="list-reset flex flex-row md:flex-col py-0 md:py-3 px-1 md:px-2 text-center md:text-left"
      >
        <BaseItem
          v-for="(obj, key) in sideBarItems"
          :key="key"
          :name="obj.name"
          :icon="obj.icon"
          :color="obj.color"
          :href="obj.href"
        />
      </ul>
    </div>
  </div>
</template>

<script>
import BaseItem from '~/layouts/SideBar/BaseItem';
import sideBarItemsList from './items-list.json';

export default {
  components: {
    BaseItem
  },
  computed: {
    sideBarItems() {
      return sideBarItemsList;
    }
  }
};
</script>
