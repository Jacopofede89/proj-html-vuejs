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
    <div class="box_text">
        <div class="box_text_pic">
            <h1>Graphic Design</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit,Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
            <img src="@/assets/home-6-service-image-01.png">
        </div>
        <div class="box_text_pic">
            <h1>Graphic Design</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit,Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
            <img src="@/assets/home-6-service-image-02.png">
        </div>
        <div class="box_text_pic">
            <h1>Graphic Design</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit,Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
            <img src="@/assets/home-6-service-image-03.png">
        </div>
        <div class="box_text_pic">
            <h1>Graphic Design</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit,Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
            <img src="@/assets/home-6-service-image-04.png">
        </div>
    </div>
    <div class="box_text">
        <div class="box_text_right">
            <h5>TOGHETER WE CAN CREATE</h5>
            <div class="color">SERVICES WE <span>CAN PROVIDE</span> FOR MY CLIENTS</div>
            <ul>
                <li><i class="fas fa-check"></i> io</li>
                <li><i class="fas fa-check"></i> io</li>
                <li><i class="fas fa-check"></i> io</li>
                <li><i class="fas fa-check"></i> io</li>
            </ul>
            <button>Get started for free</button>
        </div>
    </div>
    
  </div>
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
}.box_text{
    display: flex;
    flex-wrap:wrap;
    margin: 0 auto;
    width:45%;
    height: 750px;
    border:2px solid black;
}.box_text_pic{
    margin: auto;
    border:2px solid red;
    width:45%;
    // height: 50%;
    text-align: initial;
    img{
        margin-top:20px;
        width: 90%;
    }
}.box_text_right{
    margin-top:200px;
    text-align: initial;

    ul {
  list-style-type: none;
  padding: 0;
}
}
</style>
