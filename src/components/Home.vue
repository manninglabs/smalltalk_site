<template>
	<div>
		<div class="nav">
  		<img src="../assets/logo.svg" class="logo" />
  		<div class="text-logo">smalltalk</div>
  	</div>
	  <div class="section">
	    <h1>Text Your Customers.<br />Sell More Stuff.</h1>
	    <h4>Launch your own AI powered shopping assistant today.</h4>
	    <p><a href="mailto:hi@gosmalltalk.com">hi@gosmalltalk.com</a></p>
	  </div>
	  <div class="section brand-logos">
	  	<!-- <hr /> -->
	  	<a href="http://www.ab-inbev.com" target="_blank"><img src="../assets/abinbev.png" class="brand-logo" /></a>
	  	<a href="http://www.techstars.com" target="_blank"><img src="../assets/techstars.png" class="brand-logo" /></a>
	  	<a href="https://drinkeasy.co" target="_blank"><img src="../assets/drinkeasy.png" class="brand-logo" /></a>
	  	<!-- <a href="http://www.jashanmalgroup.com" target="_blank"><img src="../assets/jashanmal.png" class="brand-logo" /></a> -->
	  	<a href="https://www.textshopornot.com" target="_blank"><img src="../assets/toshopornot.png" class="brand-logo" /></a>
	  </div>
	  <div class="section">
	  	<h2>How Does It Work?</h2>
	  	<h3>1. Connect Your Inventory.</h3>
	  	<img src="../assets/screenshot-1.png" class="mockup" />
	  	<h3>2. Choose Your Channels.</h3>
	  	<img src="../assets/screenshot-2.png" class="mockup" />
	  	<h3>3. Say "Hi" 👋 and Start Selling.</h3>
	  	<img src="../assets/screenshot-3.png" class="mockup" />
	  </div>
	  <div class="section">

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
	padding-top: 50px;
	padding-bottom: 50px;
}
.brand-logos img {
	margin: 30px;
}
.mockup {
  width: 80%;
  margin: 0px;
}
</style>
