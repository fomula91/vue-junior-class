<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <!-- 컴포넌트 명명법 종류 -->
    <!-- <hello-world msg="my components"></hello-world> 케밥케이스
    <HelloWorld></HelloWorld> 파스칼 케이스
    <HelloWorld /> 축양형-->
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  // 인스턴스 옵션속성, 컴포넌트 옵션 속성을 넣으면 된다.
  name: "App",
  components: {
    HelloWorld,
  },
};
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
