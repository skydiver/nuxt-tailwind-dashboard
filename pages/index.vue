<template>
  <BaseContainer>
    <PageHeader title="HELLO WORLD!" />
    <MetricCards />
    <GraphCards />
  </BaseContainer>
</template>

<script>
import BaseContainer from '~/components/containers/BaseContainer.vue';
import PageHeader from '~/components/widgets/PageHeader.vue';

import MetricCards from '~/components/_demo/MetricCards.vue';
import GraphCards from '~/components/_demo/GraphCards.vue';

export default {
  components: {
    BaseContainer,
    PageHeader,
    MetricCards,
    GraphCards
  }
};
</script>
