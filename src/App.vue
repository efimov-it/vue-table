<template>
  <div class="main-wrapper">
    <img src="./assets/logo.svg" class="logo"/>
    <h1>Vue-table</h1>
    <p class="description">A Vue js component for easy table creation</p>
    <VueTable />
  </div>
</template>

<script>
import VueTable from './vue-table';
export default {
  name: 'App',
  components: {VueTable}
}
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #2a2f2a;
  box-sizing: border-box;
}
body {
  background-color: #f5f5f5;
}
.main-wrapper{
  background-color: #ffffff;
  max-width: 1024px;
  min-height: 100vh;
  margin: 0px auto;
  padding: 0px 20px;
}
.logo {
  display: block;
  width: 25%;
  margin: 0px auto;
  padding-top: 30px;
}
h1 {
  padding: 20px 0px 10px 0px;
  text-align: center;
}
.description {
  text-align: center;
  color: #555555;
  margin-bottom: 20px;
}
</style>
