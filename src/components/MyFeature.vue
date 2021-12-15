<template>
<section>
    <div class="text">
      <h6>Choose a course to get started</h6>
      <p>Leatest Featured <span>Courses</span></p>
    </div>
    <div class="box">
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/course-02-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$40.00</h5>
                <h5>Learning to Write as a Professional</h5>
                <h5>Author</h5>
                <span><i class="far fa-file-alt"></i> 20 lessons</span> <span><i class="fas fa-user-graduate"></i> 50 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/stock-full-hd-03-480x298.jpg">
            </div>
            <div class="text_">
                <h5>Free</h5>
                <h5>Customer-centric Info-Tech</h5>
                <h5>Strategies</h5>
                <span><i class="far fa-file-alt"></i> 24 lessons</span> <span><i class="fas fa-user-graduate"></i> 769 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/stock-full-hd-04-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$19.00</h5>
                <h5>Opening Programming Courses for</h5>
                <h5>Everyone:Python</h5>
                <span><i class="far fa-file-alt"></i> 17 lessons</span> <span><i class="fas fa-user-graduate"></i> 62 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/stock-full-hd-06-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$26.00</h5>
                <h5>Academic Listening and Note-</h5>
                <h5>taking</h5>
                <span><i class="far fa-file-alt"></i> 14 lessons</span> <span><i class="fas fa-user-graduate"></i> 67 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/course-featured-image-01-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$39.00</h5>
                <h5>Master jQuery in a Short Period of</h5>
                <h5>Time</h5>
                <span><i class="far fa-file-alt"></i> 6 lessons</span> <span><i class="fas fa-user-graduate"></i> 51 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/stock-full-hd-05-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$59.00</h5>
                <h5>Introduction to Javascript for</h5>
                <h5>Beginners</h5>
                <span><i class="far fa-file-alt"></i> 14 lessons</span> <span><i class="fas fa-user-graduate"></i> 76 students </span>
            </div>
        </div>
    </div>
    <button>View all courses <i class="fas fa-long-arrow-alt-right"></i></button>
</section>
</template>

<script>
export default {
  name: 'MyFeature'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
  margin: 150px auto;  
  width:100%;
  height: 750px;
  background-color:rgba(245,247,250,255);
}.text{
    padding: 50px;
    h6{
       color: grey;
    }p{
        font-size: 30px;
        font-weight: bold;
    }span{
        color:rgba(32,173,150,255);
        font-weight: normal;
    }

}.box{
    display: flex;
    flex-wrap:wrap;
    margin:auto;
    width: 80%;
    height:500px;
    // border:2px solid black;
}.box_text{
    display: flex;
    margin:0 auto;
    // border:2px solid white;
    width:49%;
    height: 33%;
    text-align: initial;
}.pic img{ 
    display: flex;
    border-radius: 50%;
    width: 120px;
    height: 120px;
}.text_{
    width:60%;
    padding: 20px;
    h5:first-child{color:rgba(32,173,150,255)}
    h5:hover{
        color:rgba(32,173,150,255);
        cursor: pointer;
    }
    span{
        color: grey;
        font-size: 10px;
        margin-right: 10px;
    }
    // border:2px solid blue;
}button{
    border:none;
    background-color:rgba(32,173,150,255);
    color: white;
    font-weight: bold;
    color:white;
    border-radius:3px;
    padding:10px 50px;
    margin-top:10px;
}
</style>
