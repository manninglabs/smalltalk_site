<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
@font-face {
  font-family: 'Colfax-Regular';
  src: url('assets/Colfax-Regular.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: 'Colfax-Medium';
  src: url('assets/Colfax-Medium.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

#app {
  font-family: 'Colfax-Regular', sans-serif;
}

h1 {
  font-family: 'Colfax-Medium', sans-serif;
  font-size: 50px;
  font-weight: normal;
}
h2 {
  font-family: 'Colfax-Regular', sans-serif;
  font-size: 40px;
  font-weight: normal;
}
h3 {
  font-size: 26px;
  font-weight: normal;
}
body {
  margin: 0 0 40px;
}
.footer {
  position: absolute;
  text-align: center;
  bottom: 0;
  height: 40px;
  background-color: #FFF;
  width: 100%;
}
.footer p {
  margin: 0px;
  padding: 0px;
  line-height: 40px;
}
</style>
