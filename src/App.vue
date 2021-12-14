<template>
  <div id="app">
    <Header/>
    <Main/>
    <MyFeature/>
    <MyPeople/>
    <MyBlog/>
    
    
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import MyFeature from './components/MyFeature.vue'
import MyPeople from './components/MyPeople.vue'
import MyBlog from './components/MyBlog.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    MyFeature,
    MyPeople,
    MyBlog,
  },
  data(){
  return {
    menu: [
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
        ]
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
