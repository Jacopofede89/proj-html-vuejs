<template>
<section>
    <div class="text">
      <h6>ENJOY READING ON MAXCOACH</h6>
      <h1>Leatest On <span>Our Blogs</span></h1>
    </div>
    <div class="box">
        <div class="box_pic">
            <img src="@/assets/artist-blog-03-480x325.jpeg">
            <h6>ARTIST</h6>
            <h4>Brush Strokes Energize Trees in</h4>
            <h4>Painting</h4>
            <span><i class="far fa-calendar"></i> May 15, 2020</span> <span><i class="far fa-eye"></i> 688 views </span>
        </div>
        <div class="box_pic">
            <img src="@/assets/artist-blog-01-480x325.jpg">
            <h6>ARTIST</h6>
            <h4>Brush Strokes Energize Trees in</h4>
            <h4>Painting</h4>
            <span><i class="far fa-calendar"></i> May 15, 2020</span> <span><i class="far fa-eye"></i> 688 views </span>
        </div>
        <div class="box_pic">
            <img src="@/assets/artist-blog-02-480x325.jpg">
            <h6>ARTIST</h6>
            <h4>Brush Strokes Energize Trees in</h4>
            <h4>Painting</h4>
            <span><i class="far fa-calendar"></i> May 15, 2020</span> <span><i class="far fa-eye"></i> 688 views </span>
        </div>
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
  height: 600px;
  background-color:rgba(245,247,250,255);
}.box{
    display: flex;
    width: 100%;
    height:500px;
    text-align: left;
    border:2px solid black;
}.box_pic{
   border:2px solid red; 
   width: 33%;
   height: 500px;
   margin: 10px;
}img{
    width: 100%;
}
</style>