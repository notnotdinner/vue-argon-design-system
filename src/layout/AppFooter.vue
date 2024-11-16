<template>
    <footer class="footer has-cards">
        <div class="container">
            <div class="row">
                <div class="col text-center">
                    <p class="text-muted">&copy; {{ currentYear }} Reotrip. All rights reserved.</p>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
  name: 'AppFooter',
  data() {
    return {
      currentYear: new Date().getFullYear()
    };
  }
};
</script>

<style scoped>
/* 添加一些样式 */
</style>