<template>
  <!-- <GreetIng name="Peter" heroName="Batman"/>
  <GreetIng name="John" heroName="Superman"/>
  <GreetIng name="Smith" heroName="Wonder Woman"/>
<GreetIng :name="name" :heroName="channel" /> -->
<div id="article">

<ArticlePage title="Article Title" :likes="50"  :isPublished="true"/>
</div>
</template>  

<script>
// import GreetIng from './components/Greet.vue'
import ArticlePage from './components/ArticlePage.vue'

export default {
  name: 'App',
  components: {
    // GreetIng,
    ArticlePage
  },
  data(){
    return {
      name: 'Vishwas',
      channel: 'Codevoluation'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
