<template>
  <Header />
  <Banner />
  <Services />
  <Discount />
  <Reason />
  <Footer />

<!--  <div id="nav">-->
<!--    <router-link to="/">Home</router-link> |-->
<!--    <router-link to="/about">About</router-link>-->
<!--  </div>-->
<!--  <router-view/>-->
</template>

<script>
import Header from './components/Header'
import Banner from './components/Banner'
import Services from './components/Services'
import Discount from './components/Discount'
import Reason from './components/Reason'
import Footer from './components/Footer'


export default{
  name: "App",
  components:{
   Header,
   Banner,
   Services,
   Discount,
   Reason,
    Footer
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
}

</style>
