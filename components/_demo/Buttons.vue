<template>
  <div class="flex flex-row flex-wrap flex-grow m-8">
    <div class="w-full">
      <Box title="Simple">
        <div class="demo__buttons-container">
          <button class="bg-grey hover:bg-grey-dark text-grey-darkest font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-red hover:bg-red-dark text-white font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-orange hover:bg-orange-dark text-orange-darkest font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-yellow hover:bg-yellow-dark text-yellow-darkest font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-green hover:bg-green-dark text-white font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-teal hover:bg-teal-dark text-white font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-blue hover:bg-blue-dark text-white font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-indigo hover:bg-indigo-dark text-white font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-purple hover:bg-purple-dark text-white font-bold py-2 px-4 rounded">Sample</button>
          <button class="bg-pink hover:bg-pink-dark text-white font-bold py-2 px-4 rounded">Sample</button>
        </div>
      </Box>
      <Box title="Pills" class="mt-8">
        <div class="demo__buttons-container">
          <button class="bg-grey hover:bg-grey-dark text-grey-darkest font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-red hover:bg-red-dark text-white font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-orange hover:bg-orange-dark text-orange-darkest font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-yellow hover:bg-yellow-dark text-yellow-darkest font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-green hover:bg-green-dark text-white font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-teal hover:bg-teal-dark text-white font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-blue hover:bg-blue-dark text-white font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-indigo hover:bg-indigo-dark text-white font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-purple hover:bg-purple-dark text-white font-bold py-2 px-4 rounded-full">Sample</button>
          <button class="bg-pink hover:bg-pink-dark text-white font-bold py-2 px-4 rounded-full">Sample</button>
        </div>
      </Box>
      <Box title="Outline" class="mt-8">
        <div class="demo__buttons-container">
          <button class="bg-transparent hover:bg-grey text-grey-dark font-semibold hover:text-white py-2 px-4 border border-grey hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-red text-red-dark font-semibold hover:text-white py-2 px-4 border border-red hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-orange text-orange-dark font-semibold hover:text-white py-2 px-4 border border-orange hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-yellow text-yellow-dark font-semibold hover:text-white py-2 px-4 border border-yellow hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-green text-green-dark font-semibold hover:text-white py-2 px-4 border border-green hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-teal text-teal-dark font-semibold hover:text-white py-2 px-4 border border-teal hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-blue text-blue-dark font-semibold hover:text-white py-2 px-4 border border-blue hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-indigo text-indigo-dark font-semibold hover:text-white py-2 px-4 border border-indigo hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-purple text-purple-dark font-semibold hover:text-white py-2 px-4 border border-purple hover:border-transparent rounded">Sample</button>
          <button class="bg-transparent hover:bg-pink text-pink-dark font-semibold hover:text-white py-2 px-4 border border-pink hover:border-transparent rounded">Sample</button>
        </div>
      </Box>
      <Box title="3D" class="mt-8">
        <div class="demo__buttons-container">
          <button class="bg-grey hover:bg-grey-light text-grey-darkest font-bold py-2 px-4 border-b-4 border-grey-dark hover:border-grey rounded">Sample</button>
          <button class="bg-red hover:bg-red-light text-white font-bold py-2 px-4 border-b-4 border-red-dark hover:border-red rounded">Sample</button>
          <button class="bg-orange hover:bg-orange-light text-orange-darkest font-bold py-2 px-4 border-b-4 border-orange-dark hover:border-orange rounded">Sample</button>
          <button class="bg-yellow hover:bg-yellow-light text-yellow-darkest font-bold py-2 px-4 border-b-4 border-yellow-dark hover:border-yellow rounded">Sample</button>
          <button class="bg-green hover:bg-green-light text-white font-bold py-2 px-4 border-b-4 border-green-dark hover:border-green rounded">Sample</button>
          <button class="bg-teal hover:bg-teal-light text-white font-bold py-2 px-4 border-b-4 border-teal-dark hover:border-teal rounded">Sample</button>
          <button class="bg-blue hover:bg-blue-light text-white font-bold py-2 px-4 border-b-4 border-blue-dark hover:border-blue rounded">Sample</button>
          <button class="bg-indigo hover:bg-indigo-light text-white font-bold py-2 px-4 border-b-4 border-indigo-dark hover:border-indigo rounded">Sample</button>
          <button class="bg-purple hover:bg-purple-light text-white font-bold py-2 px-4 border-b-4 border-purple-dark hover:border-purple rounded">Sample</button>
          <button class="bg-pink hover:bg-pink-light text-white font-bold py-2 px-4 border-b-4 border-pink-dark hover:border-pink rounded">Sample</button>
        </div>
      </Box>
    </div>
  </div>
</template>

<script>
import Box from '~/components/containers/Box.vue';

export default {
  components: {
    Box,
  },
};
</script>

<style scoped>
.demo__buttons-container {
  text-align: center;
}

.demo__buttons-container span {
  display: inline-flex;
}
</style>
