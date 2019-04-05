<template>
  <div class="flex flex-wrap">
    <MetricCard
      card-color="bg-green-lightest"
      card-border-color="border-green-dark"
      icon="fa-wallet"
      icon-color="green-dark"
      title="Total Revenue"
      value="$3249"
      arrow="up"
      arrow-color="green"
    />
    <MetricCard
      card-color="bg-orange-lightest"
      card-border-color="border-orange"
      icon="fa-users"
      icon-color="orange-dark"
      title="Total Users"
      value="249"
      arrow="equal"
      arrow-color="orange"
    />
    <MetricCard
      card-color="bg-yellow-lightest"
      card-border-color="border-yellow-dark"
      icon="fa-user-plus"
      icon-color="yellow-dark"
      title="New Users"
      value="2"
      arrow="up"
      arrow-color="yellow-dark"
    />

    <MetricCard
      card-color="bg-blue-lightest"
      card-border-color="border-blue"
      icon="fa-server"
      icon-color="blue-dark"
      title="Server Uptime"
      value="152 days"
    />
    <MetricCard
      card-color="bg-indigo-lightest"
      card-border-color="border-indigo"
      icon="fa-tasks"
      icon-color="indigo-dark"
      title="To Do List"
      value="7 tasks"
    />
    <MetricCard
      card-color="bg-red-lightest"
      card-border-color="border-red"
      icon="fa-inbox"
      icon-color="red-dark"
      title="Issues"
      value="3"
      arrow="up"
      arrow-color="red"
    />
  </div>
</template>

<script>
import MetricCard from '~/components/widgets/MetricCard.vue';

export default {
  components: {
    MetricCard
  }
};
</script>
