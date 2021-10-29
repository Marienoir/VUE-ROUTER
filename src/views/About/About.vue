<template>
  <div class="about">
    <div class="details">
      <h3>Personal Details</h3>
      <h5>
        <span>Email:</span><br />
        okosunmaryeghonghon@gmail.com
      </h5>
      <h5>
        <span>Location:</span><br />
        Lagos, Nigeria
      </h5>
      <h5>
        <span>Nationality:</span><br />
        Nigerian
      </h5>
      <h5>
        <span>Portfolio:</span><br />
        <a target="_blank" :href="link">https://dev-marienoir.netlify.app/</a>
      </h5>
    </div>
    <div>
      <p>
        I am result oriented and dedicated to creating user-friendly websites. I
        enjoy learning new concepts and I have written few technical articles. I
        write and blog about my experiences, short-comings and victories in my
        journey as a developer.
        <br /><br />
        Technologies I am most familiar with includes <span>Tailwind CSS</span>,
        <span>Bootstrap</span>, <span>Git</span> and <span>JavaScript</span>.
        However I am also trying to learn some front-end frameworks like
        <span>Vue JS</span> and <span>React</span>. I am quite familiar with backend
        languages like <span>Node</span> and <span>Nest JS.</span><br><br>
        When I am not coding, I am either seeing a Sci-Fi movie or reading a
        novel.
      </p>
      <h4>Mary Okosun</h4>
      <nav>
        <router-link :to="{ name: 'enyata' }"> About Enyata </router-link>
        <router-view />
      </nav>
    </div>
  </div>
</template>
<script>
export default {
  name: "About",
  data(){
    return{
      link: "https://dev-marienoir.netlify.app/"
    }
  }
}
</script>
<style scoped>
.about {
  max-width: 1140px;
  display: flex;
  margin: auto;
}
a{
  text-decoration: none;
  color: black;
}
h1 {
  text-transform: uppercase;
}
span {
  color: rgb(236, 93, 93);
}
.details {
  margin-right: 30px;
}
span {
  font-weight: bold;
}
h4 {
  font-family: "Lobster", cursive;
  font-size: 25px;
}
p {
  background: rgb(243, 232, 232);
  color: rgb(58, 56, 56);
  padding: 40px;
  font-size: 18px;
  line-height: 30px;
}
nav {
  margin-top: 20px;
}
nav a {
  color: rgb(236, 93, 93);
  border-bottom: 3px solid;
  text-decoration: none;
  font-size: 18px;
  cursor: pointer;
}
</style>
