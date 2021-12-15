<template>
  <div id="app">
    <MyHeader :navs="this.nav"/>
    <MyMain/>
    <MyFeature/>
    <MyPeople/>
    <MyBlog/>
    <MyHelp/>
    <MyFooter
    :links="this.link"
    :names="this.name"
    :sites="this.site"
    :contact="this.contact"
    />
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFeature from './components/MyFeature.vue'
import MyPeople from './components/MyPeople.vue'
import MyBlog from './components/MyBlog.vue'
import MyHelp from './components/MyHelp.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFeature,
    MyPeople,
    MyBlog,
    MyHelp,
    MyFooter,
  },
  data(){
  return {
    nav: [
             {
                 text: "Home",
                 visible: false
             },
             {
                 text: "Pages",
                 visible: false
             },
             {
                 text: "Courses",
                 visible: false
             },
             {
                 text: "Features",
                 visible: false
             },
             {
                 text: "Blog",
                 visible: false
             },
             {
                 text: "Shop",
                 visible: false
             }
        ],
        // footer --->
    link: [
             {
                 text: "Explore",
                 visible: true
             },
             {
                 text: "Start here",
                 visible: false
             },
             {
                 text: "Blog",
                 visible: false
             },
             {
                 text: "About us",
                 visible: false
             },
             
         ],
    name: [
             {
                 text:" .",
                 visible: true
             },
             {
                 text: "Success story",
                 visible: false
             },
             {
                 text: "Courses",
                 visible: false
             },
             {
                 text: "Contact us",
                 visible: false
             },
             
         ],
    site: [
             {
                 text: "Information",
                 visible: true
             },
             {
                 text: "Membership",
                 visible: false
             },
             {
                 text: "Purchase guide",
                 visible: false
             },
             {
                 text: "Privacy policy",
                 visible: false
             },
             {
                 text: "Terms of service",
                 visible: false
             },
             
             ],
    contact : {
      address : "63 E. Studebaker Street Bolingbrook, IL 60440",
      phone : "+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday",
      email : "support@maxcoach.com",
    }
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
*{
  margin:0;
}
</style>
