<template>
  <div class="relative inline-block">
    <button
      class="drop-button text-white focus:outline-none"
      @click.prevent="toggleDD('userDropDown')"
    >
      <span class="pr-2">
        <img
          class="w-6 h-6 rounded-full"
          src="http://i.pravatar.cc/100"
          alt="Avatar of User"
        />
      </span>
      Hi, User
      <svg
        class="h-3 ml-1 fill-current"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 20 20"
      >
        <path
          d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
        />
      </svg>
    </button>
    <div
      id="userDropDown"
      class="dropdownlist absolute bg-black text-white pin-r mt-3 p-3 overflow-auto z-30 invisible"
    >
      <a
        href="#"
        class="p-2 hover:bg-grey-darkest text-white text-sm no-underline hover:no-underline block"
        ><i class="fa fa-user fa-fw"></i> Profile</a
      >
      <a
        href="#"
        class="p-2 hover:bg-grey-darkest text-white text-sm no-underline hover:no-underline block"
        ><i class="fa fa-cog fa-fw"></i> Settings</a
      >
      <div class="border border-grey-darkest"></div>
      <a
        href="#"
        class="p-2 hover:bg-grey-darkest text-white text-sm no-underline hover:no-underline block"
        ><i class="fas fa-sign-out-alt fa-fw"></i> Log Out</a
      >
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    window.onclick = event => {
      if (
        !event.target.matches('.drop-button') &&
        !event.target.matches('.drop-search')
      ) {
        const dropdowns = document.getElementsByClassName('dropdownlist');
        for (let i = 0; i < dropdowns.length; i++) {
          const openDropdown = dropdowns[i];
          if (!openDropdown.classList.contains('invisible')) {
            openDropdown.classList.add('invisible');
          }
        }
      }
    };
  },
  methods: {
    toggleDD(myDropMenu) {
      document.getElementById(myDropMenu).classList.toggle('invisible');
    }
  }
};
</script>

<style lang="scss" scoped>
#userDropDown {
  min-width: 200px;
}

button {
  display: flex;
  align-items: center;
}
</style>
