<template>
<section>
    <div class="text">
      <h6>Choose a course to get started</h6>
      <h1>Leatest Featured Courses</h1>
    </div>
    <div class="box">
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/course-02-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$40.00</h5>
                <h5>Choose a course to get started</h5>
                <h5>Author</h5>
                <span><i class="far fa-file-alt"></i> 20 lessons</span> <span><i class="fas fa-user-graduate"></i> 50 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/course-02-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$40.00</h5>
                <h5>Choose a course to get started</h5>
                <h5>Author</h5>
                <span><i class="far fa-file-alt"></i> 20 lessons</span> <span><i class="fas fa-user-graduate"></i> 50 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/course-02-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$40.00</h5>
                <h5>Choose a course to get started</h5>
                <h5>Author</h5>
                <span><i class="far fa-file-alt"></i> 20 lessons</span> <span><i class="fas fa-user-graduate"></i> 50 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/course-02-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$40.00</h5>
                <h5>Choose a course to get started</h5>
                <h5>Author</h5>
                <span><i class="far fa-file-alt"></i> 20 lessons</span> <span><i class="fas fa-user-graduate"></i> 50 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/course-02-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$40.00</h5>
                <h5>Choose a course to get started</h5>
                <h5>Author</h5>
                <span><i class="far fa-file-alt"></i> 20 lessons</span> <span><i class="fas fa-user-graduate"></i> 50 students </span>
            </div>
        </div>
        <div class="box_text">
            <div class="pic">
                <img src="@/assets/course-02-480x298.jpg">
            </div>
            <div class="text_">
                <h5>$40.00</h5>
                <h5>Choose a course to get started</h5>
                <h5>Author</h5>
                <span><i class="far fa-file-alt"></i> 20 lessons</span> <span><i class="fas fa-user-graduate"></i> 50 students </span>
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
  margin: 0 auto;  
  width:80%;
  height: 600px;
  background-color:rgba(245,247,250,255);
}.box{
    display: flex;
    flex-wrap:wrap;
    width: 100%;
    height:500px;
    border:2px solid black;
}.box_text{
    display: flex;
    margin:0 auto;
    border:2px solid white;
    width:49%;
    height: 33%;
    text-align: initial;
}.pic img{ 
    display: flex;
    border-radius: 50%;
    width: 150px;
}.text_{
    width:60%;
    border:2px solid blue;


}button{
    border:none;
    background-color:rgba(32,173,150,255);
    color: white;
    font-weight: bold;
}
</style>
