<template>
	<div>
	  <div class="section">
	  	<div class="nav">
	  		<img src="../assets/logo.svg" class="logo" />
	  		<div class="text-logo">smalltalk</div>
	  	</div>
	    <h1>Sell more stuff.</h1>
	    <h4>Launch your own AI powered shopping assistant today.</h4>
	    <p><a href="mailto:hi@gosmalltalk.com">hi@gosmalltalk.com</a></p>
	  </div>
	  <div class="section brand-logos">
	  	<hr />
	  	<a href="http://www.ab-inbev.com" target="_blank"><img src="../assets/abinbev.png" class="brand-logo" /></a>
	  	<a href="http://www.techstars.com" target="_blank"><img src="../assets/techstars.png" class="brand-logo" /></a>
	  	<a href="https://drinkeasy.co" target="_blank"><img src="../assets/drinkeasy.png" class="brand-logo" /></a>
	  	<a href="http://www.jashanmalgroup.com" target="_blank"><img src="../assets/jashanmal.png" class="brand-logo" /></a>
	  	<a href="https://www.textshopornot.com" target="_blank"><img src="../assets/toshopornot.png" class="brand-logo" /></a>
	  </div>
	  <div class="section">
	  	
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
.brand-logos {
	padding-top: 180px;
}
.brand-logos img {
	margin: 30px;
}
</style>
