<template>
  <div class="dashboard">
    <Sidebar />
    <div class="content">
      <h1>Dashboard</h1>
      <p>Welcome to the Dashboard!</p>
    </div>
  </div>
</template>

<script>
import Sidebar from '@/components/Sidebar.vue';

export default {
  name: 'Dashboard',
  components: {
    Sidebar
  }
};
</script>

<style scoped>
.dashboard {
  display: flex;
}

.content {
  flex: 1;
  padding: 20px;
}
</style>