<template>
  <BaseContainer>
    <PageHeader title="Buttons" />
    <ButtonsDemo />
  </BaseContainer>
</template>

<script>
import BaseContainer from '~/components/containers/BaseContainer.vue';
import PageHeader from '~/components/widgets/PageHeader.vue';

import ButtonsDemo from '~/components/_demo/Buttons.vue';

export default {
  components: {
    BaseContainer,
    PageHeader,
    ButtonsDemo
  }
};
</script>
