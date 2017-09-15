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
}
@font-face {
  font-family: 'Colfax-Medium';
  src: url('assets/Colfax-Medium.ttf') format('truetype');
}
@font-face {
  font-family: 'Colfax-Bold';
  src: url('assets/Colfax-Bold.ttf') format('truetype');
}

#app {
  font-family: 'Colfax-Regular', sans-serif;
}

h1 {
  font-family: 'Colfax-Medium', sans-serif;
  font-size: 72px;
  line-height: 80px;
  margin: 0px;
  font-weight: normal;
}
h2 {
  font-size: 48px;
  line-height: 56px;
  margin-bottom: 32px;
  font-weight: normal;
}
h3 {
  font-size: 32px;
  line-height: 40px;
  margin-bottom: 32px;
  font-weight: normal;
}
h4 {
  font-size: 24px;
  line-height: 32px;
  margin-bottom: 32px;
  font-weight: normal;
}
p {
  font-size: 16px;
  line-height: 24px;
}
a {
  text-decoration: underline;
  color: #000;
}
a:hover {
  text-decoration: underline;
  color: #999;
}
a:active {
  text-decoration: underline;
  color: #AAA;
}
small {
  font-size: 12px;
  line-height: 16px;
}
body {
  margin: 0px;
  margin-bottom: 40px; /* match .footer height */
}
.footer {
  position: absolute;
  text-align: center;
  bottom: 0;
  height: 40px; /* match body margin */
  background-color: #FFF;
  width: 100%;
}
.footer p {
  margin: 0px;
  padding: 0px;
  line-height: 40px;
}
</style>
