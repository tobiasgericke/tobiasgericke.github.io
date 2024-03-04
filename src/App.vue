<template>
  <div id="app">
    <Title></Title>
    <About></About>
    <Projects></Projects>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<script setup>
import Title from './components/Title'
import About from './components/About'
import Projects from './components/Projects'
import Contact from './components/Contact'
import Footer from './components/Footer'

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
