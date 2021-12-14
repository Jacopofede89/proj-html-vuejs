<template>
<section>
  <div class="nav">
    <ul>
      <li><img class="logo" src="@/assets/dark-logo.png"></li>
      <li v-for="nav, i in navs" :key="i">{{nav.text}}<i class="fas fa-sort-down"></i></li>
      <li><i class="fas fa-shopping-cart"></i></li>
      <li><i class="far fa-user-circle"></i></li>
      <li><input placeholder="search"><i class="fas fa-search"></i></li>
    </ul>    
    <div class="text">
      <h1>Learn At Your Own Pace!</h1>
      <h6>Get teammed up with people of the same will.</h6>
      <button>Get started for free</button>
    </div>
    <div class="img">
      <img class="left" src="@/assets/home-6-hero-left-person.png">
      <img id="youtube" src="@/assets/icon-youtube-play.png">
      <img class="middle" src="@/assets/home-6-hero-poster-final.jpg">
      <img class="right" src="@/assets/home-6-hero-right-person.png">
    </div>
  </div>
</section>
  
</template>

<script>
export default {
  name: 'MyHeader',
  props: {
    navs : Array,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
  width:100%;
  height: 500px;
  background-color:rgba(31,31,82,255);
}.nav{
  color: white;
  font-weight: bold;
}button{
  color:white;
  border:none;
  background-color:rgba(32,173,150,255);
  border-radius:3px;
  padding:5px 20px;
  margin-top:10px;
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
}#youtube{
  position: absolute;
  width: 35px;
  height: 35px;
  top:50%;
  right: 50%;
  z-index: 999;
}.left{
  width: 20%;
  height: 300px;
}.middle{
  border:20px solid white;
  border-radius: 20px;
  height: 300px;
  position: relative;
}.right{
  width:10%;
  margin-top:30px;
  position: relative;
  top:42px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}

</style>
