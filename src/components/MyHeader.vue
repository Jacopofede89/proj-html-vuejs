<template>
<section>
  <div class="nav">
    <ul>
      <li><img class="logo" src="@/assets/light-logo.png"></li>
      <li v-for="nav, i in navs" :key="i">{{nav.text}}<i class="fas fa-sort-down"></i></li>
      <li><i class="fas fa-shopping-cart"></i></li>
      <li><i class="far fa-user-circle"></i></li>
      <li><div class="ricerca">
        <input placeholder="search..">
        <i id="i" class="fas fa-search"></i>
        </div></li>
      <!-- <li class="io"><input placeholder="search"><i id="i" class="fas fa-search"></i></li> -->
    </ul>
    <div class="aside">
      <i class="fas fa-ruler-combined"></i>
      <i class="far fa-life-ring"></i>
      <i class="far fa-file-alt"></i>
      <i class="fas fa-shopping-cart"></i>
    </div>    
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
  font-weight: bold;
  background-color:rgba(32,173,150,255);
  border-radius:3px;
  padding:5px 20px;
  margin-top:10px;
}.logo{
  margin-right:150px ;
  width: 120px;
  color: white;
}.aside{
  margin-top:40px;
  color:black;
  background-color:white;
  width: 20px;
  height: 130px;
  float: right;
  i{
    margin-bottom: 15px;
  }
}.text{
  margin-top:50px;
  color: white;
  button:hover{
    color:rgba(32,173,150,255);
    background-color:white;
    cursor: pointer;
  }
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
  position: relative;
  top:-35px;
}.middle{
  border:20px solid white;
  border-radius: 20px;
  height: 300px;
  position: relative;
  top:-65px;
  box-shadow: 5px 10px 8px rgb(220, 220, 247);
}.right{
  width:10%;
  height: 100px;
  position: relative;
  top:80px;
  object-fit: cover;
  object-position: top;
}
ul {
  list-style-type: none;
  padding:30px;
}
li {
  display: inline-block;
  margin: 0 10px;
  .ricerca{
    width: 100px;
    height: 25px;
    background-color: white;
    border-radius: 5px;
  }input{
    border:none;
    width: 70px;
  }
  
    #i{
      color:rgba(32,173,150,255);
    }
}

</style>
