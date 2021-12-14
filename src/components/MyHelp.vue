<template>
<section>
    <div class="text">
      <h6>WANNA TRANSFORM YOUR LIFE?</h6>
      <h1>Glad to <span> Help You</span> Learn</h1>
    </div>
    <div class="box">
        <div class="box_pic">
            <span><i class="far fa-flag"></i></span>
            <h4>Web Development</h4>
            <h6>Brush Strokes Energize </h6>
            <h6>Brush Strokes Energize Trees in</h6>
            <h6>Brush Strokes Energize Tre</h6>
            
        </div>
        <div class="box_pic">
            <span><i class="fas fa-cog"></i></span>
            <h4>Web Development</h4>
            <h6>Brush Strokes Energize </h6>
            <h6>Brush Strokes Energize Trees in</h6>
            <h6>Brush Strokes Energize Tre</h6>
        </div>
        <div class="box_pic">
            <span><i class="far fa-life-ring"></i></span>
            <h4>Web Development</h4>
            <h6>Brush Strokes Energize </h6>
            <h6>Brush Strokes Energize Trees in</h6>
            <h6>Brush Strokes Energize Tre</h6>
        </div>
        <div class="box_pic">
            <span><i class="fas fa-desktop"></i></span>
            <h4>Web Development</h4>
            <h6>Brush Strokes Energize </h6>
            <h6>Brush Strokes Energize Trees in</h6>
            <h6>Brush Strokes Energize Tre</h6>
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
//   height: 600px;
  background-color:rgba(245,247,250,255);
}.text span{
    color:rgba(32,173,150,255);
}.box{
    display: flex;
    width: 100%;
    height:350px;
    text-align: left;
    border:2px solid black;
}.box_pic{
   border:2px solid red; 
   width: 25%;
   height: 250px;
   margin: 10px;
   span{
       font-size:50px;
   }
}img{
    width: 100%;
}.footer{
    background-color:white;
    width: 100%;
    height: 200px;
    margin: auto;
    padding: 30px;
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