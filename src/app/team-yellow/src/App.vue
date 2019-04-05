<template>
  <div id="app">
    <ul class="product-list">
      <li class="product-list-item">
        <a href="/items/0" class="product-list-link">
          <img class="produc-list-image" src="https://loremflickr.com/250/200/cat">
          <div class="product-list-info">
            <p>title 1</p>
            <p>description 1</p>
          </div>
        </a>
      </li>
    </ul>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
