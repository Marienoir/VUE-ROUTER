<template>
  <div>
      <h1>Welcome to User Dashboard</h1>

      <div>
      <nav>
        <router-link :to="{name:'single-user', params:{id: '1'}}">Michael</router-link> |
        <router-link :to="{name:'single-user', params:{id: 'Ibukun'}}">Ibukun</router-link> |
        <router-link :to="{name:'single-user', params:{id: 'Daniel'}}">Daniel</router-link> |
        <router-link :to="{name:'single-user', params:{id: 'Mary'}}">Mary</router-link> 
      </nav>
      <router-view/>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>