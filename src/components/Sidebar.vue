<template>
  <div class="sidebar">
    <ul>
      <li><router-link to="/products">Product</router-link></li>
      <li><router-link to="/orders">Order</router-link></li>
      <li><router-link to="/channels">Channel</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Sidebar'
};
</script>

<style scoped>
.sidebar {
  width: 200px;
  background-color: #f8f9fa;
  padding: 15px;
}

.sidebar ul {
  list-style-type: none;
  padding: 0;
}

.sidebar li {
  margin: 10px 0;
}

.sidebar a {
  text-decoration: none;
  color: #333;
}
</style>