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
                <p>Let passion and determination be the guide</p>
                <p>along the way and develop at your own pace</p>
                <p>that's comfortable.</p>
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
  height: 600px;
}.box_text{
    display: flex;
    margin:0 auto;
    width:49%;
    height: 33%;
    text-align: initial;
}.text_{
    font-size: 20px;
    padding: 40px;

}.pic img{ 
    margin-top:40px ;
    display: flex;
    border-radius: 50%;
    width: 150px;
}img{
    padding: 20px;
    margin-top: 40px;
}
</style>