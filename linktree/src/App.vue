<template>
  <main class="main">

    <!-- title -->
    <div class="title">
      <h1>링크트리 만들기</h1>
    </div>
    <!-- //title -->


    <!-- list -->
    <ul class="link-list">
      <li>
        <a class="naver" href="https://www.naver.com/" target="_blank">네이버로 이동하기</a>
      </li>
      <li>
        <a class="google" href="https://www.google.co.kr/" target="_blank">구글로 이동하기</a>
      </li>
    </ul>
    <!-- //list -->

  </main>
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
/* FFF7D4
FFD95A
C07F00
4C3D3D */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

ul {
  padding: 0;
}

li {
  list-style : none;
  margin: 50px;
}

a {
  text-decoration: none;
  color: black;
}



.title {
  width: 300px;
  background-color: #FFD95A;
  border-radius: 10px;
}

.main {
  display: flex;
  flex-direction: column;
  /* justify-content: center; */
  align-items: center;
}

.link-list {
  background-color: #FFD95A;
  border-radius: 10px;
}
.link-list li {
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: 30px;
  padding-right: 30px;

  border: 1px solid #000;
  border-radius: 10px;

  background-color: #fff;
}
.naver {
  color: green;
}

.google {
  color: blue;
}

</style>
