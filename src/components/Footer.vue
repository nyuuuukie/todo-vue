<template>
	<footer>
		<p>Made by wylex, &copy; 2021</p>
		<router-link to="/about">About</router-link>
	</footer>
</template>

<script>
	export default {
		name: 'Footer'
	}
</script>

<style scoped>
	a {
		color:#333;
	}
	
	footer {
		text-align: center;
		margin-top: 30px;
	}	
</style>