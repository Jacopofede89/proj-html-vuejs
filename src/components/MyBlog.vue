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
            <h4>Pocket-sized Notebooks Hold</h4>
            <h4>Miniature Painting</h4>
            <span><i class="far fa-calendar"></i> May 15, 2020</span> <span><i class="far fa-eye"></i> 688 views </span>
        </div>
        <div class="box_pic">
            <img src="@/assets/artist-blog-02-480x325.jpg">
            <h6>ARTIST</h6>
            <h4>Connection Between Self-</h4>
            <h4>Portaits and Identify</h4>
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
  margin: auto;  
  margin-bottom: 50px;
  width:100%;
  height: 550px;
  background-color:rgba(245,247,250,255);
  h6{color: grey;}
  .text{
      padding: 50px;
      span{
          color:rgba(32,173,150,255);
          font-weight: normal;
      }
  }
}.box{
    margin:auto;
    display: flex;
    width: 80%;
    // height:500px;
    text-align: left;
}.box_pic{
   width: 25%;
   line-height: 30px;
   span{
       color:grey;
       font-size: 10px;
       margin-right: 10px;
   }
//    height: 500px;
   margin: 10px auto;
}img{
    width: 100%;
}
</style>