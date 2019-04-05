<template>
  <div class="w-full md:w-1/2 xl:w-1/3 p-3">
    <Box title="Table">
      <table class="w-full p-5 text-grey-darker">
        <thead>
          <tr>
            <th class="text-left text-blue-darkest">Name</th>
            <th class="text-left text-blue-darkest">Side</th>
            <th class="text-left text-blue-darkest">Role</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Obi Wan Kenobi</td>
            <td>Light</td>
            <td>Jedi</td>
          </tr>
          <tr>
            <td>Greedo</td>
            <td>South</td>
            <td>Scumbag</td>
          </tr>
          <tr>
            <td>Darth Vader</td>
            <td>Dark</td>
            <td>Sith</td>
          </tr>
        </tbody>
      </table>
      <p class="py-2"><a href="#">See More issues...</a></p>
    </Box>
  </div>
</template>

<script>
import Box from '~/components/containers/Box.vue';

export default {
  components: {
    Box
  }
};
</script>
