<template>
  <section>
        <div class="main">
            <div class="link">

                <div class="address">
                    <ul>
                        <li class="title">Address</li>
                        <li>{{contact.address}}</li>
                        <li>{{contact.phone}}</li>
                        <li>{{contact.email}}</li>
                        <li class="social"><i class="fab fa-facebook-f social"></i><i class="fab fa-twitter social"></i><i class="fab fa-instagram social"></i><i class="fab fa-linkedin"></i></li>
                    </ul>
                </div>
            </div>

            <div class="link">

                <div>
                    <ul>
                        <li v-for="link, i in links" :key="i" :class="link.visible === true ? 'title' : ''">{{link.text}}</li>
                    </ul>
                </div>

                <div>
                    <ul>
                        <li v-for="name, i in names" :key="i" :class="name.visible === true ? 'title' : ''">{{name.text}}</li>
                    </ul>
                </div>

                <div>
                    <ul>
                        <li v-for="site, i in sites" :key="i" :class="site.visible === true ? 'title' : ''">{{site.text}}</li>
                    </ul>
                </div>
            </div>
        </div>
        <h5><i class="far fa-copyright"></i> 2020 Maxcoach. All Rights Reserved</h5>
      <div class="arrow"><i class="fas fa-long-arrow-alt-up"></i></div>
  </section>
</template>

<script>
export default {
  name: 'MyFooter',  
  props: {
    links : Array,
    names : Array,
    sites : Array,
    contact: Object,
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    section {
        margin: 0 auto;  
        width:100%;
        height: 350px;
        background-color: rgba(248,248,248,255);
        .main {
            width:80%;
            margin: auto;
            display: flex;
            justify-content: space-evenly;
            padding: 30px;
            .link{
                float: left;
                display: flex;
                flex-wrap: wrap;
                .title {
                    color:black;
                    font-weight: bold;
                    font-size: 15px;
                }.social{
                    font-size: 20px;
                    letter-spacing: 30px;
                }
                li {
                text-align: start;    
                list-style-type: none;
                font-size: 10px;
                color:grey;
                margin-top: 5px;
                text-transform: uppercase;
                }
                ul {
                margin-top: 20px;
                }
            }
            
        }h5{
            margin-top:80px;
            color: grey;
        }
        .arrow{
            width:50px;
            height:50px;
            border-radius: 50%;
            background-color:rgba(32,173,150,255);
            float: right;
            color: white;
            i{
                font-size: 30px;
                margin-top:10px;
            }
        }
    
    }
    
</style>
