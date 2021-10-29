<template>
  <div class="home">
    <div class="flex">
      <div>
        <h1>Hello 👋</h1>
        <h1>I am MARY OKOSUN</h1>
        <p>WEB DEVELOPER | TECHNICAL WRITER</p>
      </div>
      <div>
        <img alt="logo" src="../assets/image.png" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>
<style scoped>
.home {
  max-width: 1140px;
  margin:0 auto;
}
.flex {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
img{
  height: 450px;
}
button {
  background: rgb(228, 39, 39);
  padding: 20px 20px;
  width: 150px;
  color: #fff;
  font-size: 19px;
  border-radius: 5px;
  border: none;
}
</style>
