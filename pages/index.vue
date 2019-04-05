<template>
  <BaseContainer>
    <PageHeader title="HELLO WORLD!" />
    <MetricCards />
  </BaseContainer>
</template>

<script>
import BaseContainer from '~/components/containers/BaseContainer.vue';
import PageHeader from '~/components/widgets/PageHeader.vue';
import MetricCards from '~/components/_demo/MetricCards.vue';

export default {
  components: {
    BaseContainer,
    PageHeader,
    MetricCards
  }
};
</script>
