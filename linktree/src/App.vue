<template>
  <section>
    <h1>링크트리 만들기</h1>
    <ul>
      <li>
        <a class="naver" href="https://www.naver.com/" target="_blank">네이버로 이동하기</a>
      </li>
      <li>
        <a class="google" href="https://www.google.co.kr/" target="_blank">구글로 이동하기</a>
      </li>
    </ul>
    
    
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </section>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
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
li {
  list-style : none;
  margin: 50px;
}
a {
  text-decoration: none;
  color: black;
}
.naver {
  color: green;
}
.google {
  color: blue;
}
</style>
