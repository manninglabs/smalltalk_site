<template>
	<div>
	  <div class="section">
	  	<div class="nav"><img src="../assets/logo.svg" class="logo" /></div>
	    <h1>smalltalk</h1>
	    <h4>conversational commerce as a service</h4>
	    <p><a href="mailto:harry@gosmalltalk.com">harry@gosmalltalk.com</a></p>
	  </div>
	  <div class="section logo-section">
	  	<a href="http://www.ab-inbev.com" target="_blank"><img src="../assets/abinbev.png" class="brand-logo" /></a>
	  	<a href="http://www.techstars.com" target="_blank"><img src="../assets/techstars.png" class="brand-logo" /></a>
	  	<a href="https://drinkeasy.co" target="_blank"><img src="../assets/drinkeasy.png" class="brand-logo" /></a>
	  	<a href="http://www.jashanmalgroup.com" target="_blank"><img src="../assets/jashanmal.png" class="brand-logo" /></a>
	  </div>
	  <div class="footer">
	    <p><small>© 2017 Swig Labs Inc. All Rights Reserved</small></p>
	  </div>
	</div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style scoped>
.section, .alt-section {
	width: 100%;
	min-height: 300px;
	text-align: center;
}
.alt-section {
	background-color: #EEE;
}
.brand-logo {
	height: 40px;
	margin: 0px 20px;
}
.logo-section {
	height: 230px;
}
.logo-section img {
	margin-top: 180px;
}
</style>
