<template>
    <p class = 'heading'>PROSHORE</p>
    <div class="img-box">
      <img src="./assets/proshore.png">
    </div>
  <SignUpForm/>


</template>

<script>
import SignUpForm from './components/SignUpForm.vue'
export default {
  name: 'App',
  components: { SignUpForm }
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
body{
  margin: 0;
  background: #eee;
}
.heading{
  text-align: center;
  letter-spacing: 10px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  text-decoration: bold;
  font-size:35px;

}


</style>
