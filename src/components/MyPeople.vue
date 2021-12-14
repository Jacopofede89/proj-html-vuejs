<template>
<section>
    <div class="text">
      <h1>Why People Talk About<span> Max Coach</span>?</h1>
    </div>
    <div class="box_text">
            <div class="pic">
                <img src="@/assets/testimonial-avata-02.jpg">
            </div>
        <div class="text_">
                <p>I am free to learn at my own pace, follow</p>
                <p>my own schedule and choose the subject I</p>
                <p>like. Great study portal for people like me.</p>
            <div class="name">
                <h6>MINA HOLLACE</h6>
                <h6>/Freelancer</h6>
            </div>
        </div>
    </div>
    <img src="@/assets/client-logo-colored-01.png">
    <img src="@/assets/client-logo-colored-02.png">
    <img src="@/assets/client-logo-colored-03.png">
    <img src="@/assets/client-logo-colored-04.png">
    <img src="@/assets/client-logo-colored-05.png">
</section>
</template>

<script>
export default {
  name: 'MyPeople'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
  margin: 0 auto;  
  width:80%;
  height: 500px;
  span{color:rgba(32,173,150,255);}
}.box_text{
    display: flex;
    margin:0 auto;
    width:70%;
    text-align: initial;
}.text_{
    font-size: 20px;
    padding: 40px;

}.pic img{ 
    margin-top:20px ;
    display: flex;
    border-radius: 50%;
    width: 150px;
}img{
    padding: 20px;
    margin-top: 40px;
}.name{
    margin-top: 20px;
    h6:nth-child(2){color:grey}
}
</style>