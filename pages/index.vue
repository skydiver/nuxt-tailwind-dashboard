<template>
  <BaseContainer>
    <PageHeader title="HELLO WORLD!" />
  </BaseContainer>
</template>

<script>
import BaseContainer from '~/components/containers/BaseContainer.vue';
import PageHeader from '~/components/widgets/PageHeader.vue';

export default {
  components: {
    BaseContainer,
    PageHeader
  }
};
</script>
