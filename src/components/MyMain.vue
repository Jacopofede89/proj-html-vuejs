<template>
<section>
  <div class="text">
        <p>Let passion and determination be the guide</p><br>
        <p>along the way and develop at your own pace</p><br>
        <p>that's comfortable.</p>
        <div class="name">
            <p>FANNIE MORENO</p>
            <p>/Founder & CEO</p>
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
    <div class="box_text">
        <div class="box_text_pic">
            <h1>Graphic Design</h1>
            <p>Have a passion for graphics and arts? Show your talents with confidence and self- assertiveness.</p>
            <img src="@/assets/home-6-service-image-01.png">
        </div>
        <div id="space" class="box_text_pic">
            <h1>Business Administration</h1>
            <p>Learners are encouraged to study the mechanism and structure of system administration.</p>
            <img src="@/assets/home-6-service-image-02.png">
        </div>
        <div class="box_text_pic">
            <img src="@/assets/home-6-service-image-03.png">
            <h1>Idea Discussion</h1>
            <p>Get teamed up with the specialists who work and teach coding for years at famous universities.</p>
        </div>
        <div id="space" class="box_text_pic">
            <img src="@/assets/home-6-service-image-04.png">
            <h1>Web Development</h1>
            <p>Learn to start building a webpage from scratch. You decide your own pace, course and speed.</p>
        </div>
    </div>
    <div class="box_text">
        <div class="box_text_right">
            <h5>TOGHETER WE CAN CREATE</h5>
            <div class="color">SERVICES WE <span>CAN PROVIDE</span> FOR MY CLIENTS.</div>
            <ul>
                <li><i class="fas fa-check"></i> Select & customize to your prefernces</li>
                <li><i class="fas fa-check"></i> Change the tuttor and make arrangements</li>
                <li><i class="fas fa-check"></i> Partecipate in events to join others</li>
                <li><i class="fas fa-check"></i> Get the desired certificate delivered at house</li>
            </ul>
            <button>Get started for free</button>
        </div>
    </div>
    
  </div>
</section>
  
</template>

<script>

export default {
  name: 'MyMain',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
  margin: 0 auto;  
  width:80%;
}.text{
    margin-top: 300px;
    font-size: 25px;
    line-height: 15px;
    font-weight:bold;
}.name{
    font-size:10px;
    margin-top: 20px;
    p:nth-child(2) {
    color:grey;
}
}.session{
    display: flex;
    justify-content: center;
    justify-content: space-evenly;
    margin-top:100px;
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
    margin-top:100px;
}.box_text{
    display: flex;
    flex-wrap:wrap;
    margin: 0 auto;
    width:45%;
    height: 750px;
    #space{
        margin-top:50px ;
    }
    button:hover{
    color:white;
    background-color:rgba(48,48,96,255);
    cursor: pointer;
  }
}.box_text_pic{
    margin: auto;
    box-shadow: 10px 10px 10px 10px rgb(231, 231, 245);
    width:35%;
    height:330px;
    text-align: initial;
    padding: 25px;
    img{
        margin-top:20px;
        width: 80%;
        height: 50%;
    }
}.box_text_right{
    margin-top:200px;
    line-height:40px;
    text-align: initial;
    h5{
        color:grey;
    }
button{
  color:white;
  border:none;
  background-color:rgba(32,173,150,255);
  border-radius:3px;
  padding:5px 20px;
  margin-top:10px;
  font-weight: bold;
}.color{
    font-size: 30px;
    font-weight: bold;
    span{
       color:rgba(32,173,150,255); 
       font-weight: normal;
    }
}
ul {
  list-style-type: none;
  padding: 0;
}i{
    color:rgba(32,173,150,255);
}
}
</style>
