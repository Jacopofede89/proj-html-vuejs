<template>
<section>
  <div class="hello">
    <ul>
      <li><img class="logo" src="@/assets/dark-logo.png"></li>
      <li><a>Core Docs</a></li>
      <li><a>Forum</a></li>
      <li><a>Community Chat</a></li>
      <li><a>Twitter</a></li>
      <li><a>News</a></li>
      <li><a>News</a><i class="fas fa-chevron-down"></i></li>
      <li><input placeholder="search"></li>
    </ul>    
    <!-- <ul>
      <li v-for="menu, i in menus" :key="i">{{menu.text}}</li>
    </ul> -->
    <div class="text">
      <h1>Learn At Your Own Pace!</h1>
      <h6>Get teammed up with people of the same will.</h6>
      <button>Get started for free</button>
    </div>
    <div class="img">
      <img class="left" src="@/assets/home-6-hero-left-person.png">
      <img class="middle" src="@/assets/home-6-hero-poster-final.jpg">
      <img class="right" src="@/assets/home-6-hero-right-person.png">
    </div>
  </div>
</section>
  
</template>

<script>
export default {
  name: 'Header',
  props: {
    Menu : Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
  width:100%;
  height: 500px;
  background-color:rgba(31,31,82,255);
}.logo{
  float: left;
  width: 100px;
}.text{
  margin-top:50px;
  color: white;
}.img{
  display: flex;
  margin-left:180px;
  margin-top: 100px;
}.left{
  width: 20%;
  height: 300px;
}.middle{
  border:20px solid white;
  height: 300px;
}.right{
  width:10%;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color:white;
}
</style>
