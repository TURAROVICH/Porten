<template>
  <div id="app">
       <Header_Support/>
              <Sticky_header/>

       <Welcome/>
       <Sezon_Page/>
       <collection_2018/>
       <new_things/>
       <our_brends/>
       <footer_helper/>
       <under_footer/>
  </div>
</template>

<script>
import Header_Support from './components/header'
import Sticky_header from './components/sticky_header'
import Welcome from './components/welcome'
import Sezon_Page from './components/sezon_page'
import collection_2018 from './components/2018-collection'
import new_things from './components/new-things'
import our_brends from './components/our-brends'
import footer_helper from './components/footer'
import under_footer from './components/under-footer'
export default {
  name: 'App',
  components: {
   Header_Support,
   Sticky_header,
   Welcome,
   Sezon_Page,
   collection_2018,
   new_things,
   our_brends,
   footer_helper,
   under_footer 
   
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=PT+Sans&display=swap');
@import url('https://fonts.googleapis.com/css2?family=PT+Sans&display=swap');
html{
  scroll-behavior: smooth;
  /* transition: scroll-behavior 3s ease-in; */
}
body{
  background: #000;
}
*{
     margin: 0;
   padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
   margin: 0;
   padding: 0;
   box-sizing: border-box;
}
.line{
  border-bottom: 2px solid #fff;
  width: 120px;
  margin-top: 20px;
  margin-bottom: 5px;
}
</style>
