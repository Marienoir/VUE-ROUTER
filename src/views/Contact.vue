<template>
  <div class="main">
    <div class="image">
      <img alt="logo" src="../assets/logo.png">
      </div>
    <form>
      <div class="form-input">
        <label for="name">Name</label>
        <input type="text" placeholder="Enter Name" />
      </div>
      <div class="form-input">
        <label for="email">Email</label>
        <input type="email" placeholder="Enter Email" />
      </div>
      <div class="form-input">
        <label for="name">Message</label>
        <textarea type="text" rows="8" cols="50" placeholder="Enter Message" />
      </div>
      <div class="form-control">
        <button type="button" @click="submit">SUBMIT</button>
        
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name:"Contact",
  data(){
    return{
      message: ""
    }
  },
  methods:{
    submit(){
      this.message = "Contact Form Submitted"
      alert(this.message)
    } 
  }
};
</script>

<style>
.main{
  display: flex;
  max-width: 1140px;
  margin: auto;
  color: rgb(36, 33, 33);
}
.image img{
  width: 650px;
  height: 530px;
  margin-right: 50px;
}

form {
  background-color: rgb(226, 219, 219);
  padding: 40px 45px;
  box-shadow: 2px 2px 1px grey;
  height: 450px;
  width: 100%;
  /* max-width: 768px;
  margin: auto; */
}
/* .form{
  max-width: 76px;
  margin: 20px auto;
} */
.form-input {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin: 20px 0;
}
input {
  width: 94%;
  outline: none;
  padding: 10px;
  margin: 10px 0;
}
button {
  border: none;
  border-radius: 3px;
  padding: 20px;
  width: 100%;
  font-size: 20px;
  font-weight: bold;
  background: rgb(228, 39, 39);
  color: #fff;
}
button:hover{
  background: rgb(216, 65, 65) ;
}
</style>