// Unauthorized.vue
<template>
  <div class="unauthorized">
    <h1>Access Denied</h1>
    <p>You do not have permission to access this page.</p>
    <router-link to="/talent-dashboard">Back to Home</router-link>
  </div>
</template>

<script>
export default {
  name: "Unauthorized",
};
</script>

<style scoped>
.unauthorized {
  text-align: center;
  margin-top: 50px;
}
</style>
