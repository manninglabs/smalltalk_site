<template>
	<div>
	  <div class="section">
	  	<img src="../assets/logo.svg" class="logo" />
	    <h1>smalltalk</h1>
	    <h2>conversational commerce as a service</h2>
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
.logo {
	width: 50px;
	height: 50px;
	margin: 25px 25px;
}
</style>
