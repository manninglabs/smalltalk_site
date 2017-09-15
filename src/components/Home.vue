<template>
	<div>
	  <div class="section">
	  	<div class="nav"><img src="../assets/logo.svg" class="logo" /></div>
	    <h1>smalltalk</h1>
	    <h4>conversational commerce as a service</h4>
	    <p><a href="mailto:harry@gosmalltalk.com">harry@gosmalltalk.com</a></p>
	  </div>
	  <div class="section">
	  </div>
	  <div class="footer">
	    <p><small>© 2017 Swig Labs Inc. All Rights Reserved.</small></p>
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
.nav {
	margin: 30px 0px 100px 0px;
}
.logo {
	width: 50px;
	height: 50px;
}
</style>
