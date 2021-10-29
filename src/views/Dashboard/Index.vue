<template>
  <div>
    <h1>Welcome to Dashboard</h1>
    <div>
      <nav>
        <router-link :to="{name:'dashboard-home'}">Dashboard Home</router-link> |
        <router-link :to="{name: 'user-dashboard'}">User Dashboard</router-link>
      </nav>
      <router-view/>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>