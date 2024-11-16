<template>
  <header class="header">
    <div class="container">
      <div class="row align-items-center">
        <div class="col text-right ml-auto">
          <div class="dropdown">
            <button class="btn btn-secondary dropdown-toggle" type="button" id="userMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              {{ username }}
            </button>
            <div class="dropdown-menu dropdown-menu-right" aria-labelledby="userMenuButton">
              <a class="dropdown-item" href="#" @click="logout">Logout</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
  data() {
    return {
      username: 'John Doe' // 您可以根据实际情况动态获取用户名
    };
  },
  methods: {
    logout() {
      // 在这里添加登出逻辑
      console.log('User logged out');
    }
  }
};
</script>

<style scoped>
.header {
  background-color: #172b4d; /* Argon 深色背景 */
  padding: 20px 0;
}

.text-white {
  color: #fff;
}

.text-right {
  text-align: right;
}

.dropdown-menu-right {
  right: 0;
  left: auto;
}
</style>