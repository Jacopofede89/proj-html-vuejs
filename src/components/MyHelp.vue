<template>
<section>
    <div class="text">
      <h6>WANNA TRANSFORM YOUR LIFE?</h6>
      <h1>Glad to <span> Help You</span> Learn</h1>
    </div>
    <div class="box">
        <div class="box_pic">
            <span><i class="far fa-flag"></i></span>
            <h4>Idea Discussion</h4>
            <h6>Get teamed up with specialist</h6>
            <h6>who work and teach coding for years</h6>
            <h6>pat famous universities.</h6>
            
        </div>
        <div class="box_pic">
            <span><i class="fas fa-cog"></i></span>
            <h4>Web Development</h4>
            <h6>Learn to start building a webpage</h6>
            <h6>from scratch. You decide your own</h6>
            <h6>pace, coure and speed.</h6>
        </div>
        <div class="box_pic">
            <span><i class="far fa-life-ring"></i></span>
            <h4>System Administration</h4>
            <h6>Learners are encouraged to study</h6>
            <h6>the mechanism and structure of</h6>
            <h6>system administration.</h6>
        </div>
        <div class="box_pic">
            <span><i class="fas fa-desktop"></i></span>
            <h4>Graphic Design</h4>
            <h6>Have a passion for grapichs and </h6>
            <h6>arts? Show your talents with</h6>
            <h6>confidence and self-assertiveness.</h6>
        </div>
    </div>
    <img src="@/assets/home-6-services-image-768x308.png">
    <div class="footer">
        <h4>Start today for getting <span>Online Certification</span></h4>
        <h2>You can be your own guiding star with our help!</h2>
        <button>Get started now</button>
    </div>
    
</section>
</template>

<script>
export default {
  name: 'MyBlog',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
  margin: 0 auto;  
  width:80%;
}.text{
    span{
    color:rgba(32,173,150,255);
    font-weight: normal;
    }
}.box{
    display: flex;
    width: 100%;
    padding: 50px;
    text-align: left;
}.box_pic{
   width: 25%;
   height: 250px;
   margin: 10px;
   span{
       font-size:50px;
   }
   h6{
       color: grey;
   }
}img{
    width: 100%;
}.footer{
    background-color:white;
    width: 100%;
    height: 170px;
    margin:130px 0px auto;
    span{
        color: rgba(32,173,150,255);
        font-weight: normal;
    }
    button{
        margin-top:15px;
        border: none;
        color: white;
        background-color:rgba(32,173,150,255);
        font-weight: bold;
        padding:10px 50px;
        border-radius:5px ;
    }
}
</style>