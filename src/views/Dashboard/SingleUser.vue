<template>
  <div>
      <h1>Welcome {{user}}</h1>
      
  </div>
</template>

<script>
export default {
    name: "SingleUser",
    computed:{
        user(){
            const user= this.$route.params.id;
            return user.toUpperCase()
        }
    }
}
</script>

<style>

</style>