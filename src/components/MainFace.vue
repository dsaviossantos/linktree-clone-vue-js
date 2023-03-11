<script setup>
import { ref } from 'vue'
</script>
<template>
  
  <div class="main">
    <div class="face">
      <h1>Savio Santos</h1>
      <img alt="Face Image" style="height: 60%; width: 60%;border: 1px solid grey;border-radius: 50%; max-width: 300px;box-shadow: 1px 1px 50px; min-width: 150px; grey;" src="../assets/photo.jpg" />
    </div>
    <div class="cards">
      <div class="links">
        <a href="https://github.dsaviossantos.dev" target="_blank">
          <img alt="Github" style="height: 50px; width: 50px;" src="../assets/github.png" />
          <span>Github</span>
        </a>
      </div>
      <div class="links">
        <a href="https://linkedin.dsaviossantos.dev" target="_blank">
          <img alt="Linkedin" style="height: 50px; width: 50px;" src="../assets/linkedin.png" />
          <span>Linkedin</span>
        </a>
      </div>
      <div class="links">
        <a href="https://twitch.dsaviosantos.dev" target="_blank">
          <img alt="Twitch" style="height: 50px; width: 50px;" src="../assets/twitch.png" />
          <span>Twitch</span>
        </a>
      </div>
      <div class="links">
        <a href="yt.dsaviosantos.dev" target="_blank">
          <img alt="Youtube" style="height: 50px; width: 50px;" src="../assets/youtube.png" />
          <span>Youtube</span>
        </a>
      </div>
      <div class="links">
        <a href="https://instagram.dsaviosantos.dev" target="_blank">
          <img alt="Instagram" style="height: 50px; width: 50px;" src="../assets/instagram.png" />
          <span>Instagram</span>
        </a>
      </div>
      <div class="links">
        <a href="https://twitter.dsaviosantos.dev" target="_blank">
          <img alt="Twitter" style="height: 50px; width: 50px;" src="../assets/twitter.png" />
          <span>Twitter</span>
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
a{
  text-decoration: none;
  color: #000000;
  margin-top: 1%;
}
span{
  font-size: 30px;
  font-weight: bold;
  color: #000000;
  margin: 10px;
  float: right;
}
.face{
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 100%;
  font-size: 1.75rem;
  color: #ffffff;
}
.cards{
  max-width: 450px;
  display: block;
  margin: 0 auto;
  flex-direction: column;
}
.links{
  display: flex;
  flex-direction: row;
  justify-content: center;
  background-color: rgba( 255, 255, 255, .5);
  margin: 15px;
  min-width: 250px;
  min-height: 30px;
  border: 1px solid grey;
  border-radius: 20px;
  opacity: .9;
  box-shadow: 0 0 2em grey;
  transition: box-shadow .1s;
}

.links:hover{
  opacity: 1;
  box-shadow: 0 0 4em rgb(86, 86, 86);
}
</style>
