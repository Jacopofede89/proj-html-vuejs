<template>
<section>
  <div class="text">
        <p>Let passion and determination be the guide</p><br>
        <p>along the way and develop at your own pace</p><br>
        <p>that's comfortable.</p>
        <div class="name">
            <h6>FANNIE MORENO</h6>
            <h6>/Founder & CEO</h6>
        </div>
        <div class="session">
            <div class="session_number">
                <h1>1.926</h1>
                <p>FINISHED SESSION</p>
            </div>
            <div class="session_number">
                <h1>3.092+</h1>
                <p>ENROLLED LEARNERS</p>
            </div>
            <div class="session_number">
                <h1>200</h1>
                <p>ONLINE INSTRUCTORS</p>
            </div>
            <div class="session_number">
                <h1>100%</h1>
                <p>SATISFACTION RATE</p>
            </div>
        </div>
  </div>
  <div class="box">
    <div class="io"></div>
    <div id="mio"  class="io"></div>
    <div class="io"></div>
    <div class="io"></div>
    <div id="mio" class="io"></div>
  </div>
  <!-- <div class="box">
    <div class="io"></div>
    <div id="mio" class="io"></div>
  </div>
  <div class="box">
    <div class="io"></div>
    <div id="mio" class="io"></div>
  </div> -->
  
  
</section>
  
</template>

<script>
export default {
  name: 'Main'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
  margin: 0 auto;  
  width:80%;
  height: 700px;
  background-color: yellow;
}.text{
    margin-top: 150px;
    font-size: 25px;
    line-height: 15px;
    font-weight:bold;
}.name{
    margin-top: 20px;
    line-height: 30px;
}.session{
    display: flex;
    justify-content: center;
    justify-content: space-evenly;
    color:rgba(32,173,150,255);
}.session_number{
    line-height: 30px;
    p{
        font-size:10px;
        font-weight: bold;
        color: black;
    }
}.box{
    display: flex;
    flex-wrap:wrap;
}.io{
    width:300px;
    height: 350px;
    border:2px solid black;
    margin: 10px;
}#mio{
    margin-top:50px;
}#tuo{
    margin-top: 100px;
    width:300px;
    height: 350px;
    border:2px solid black;
    margin: 10px;
}
</style>
