<template>
	<div class="app">
		<Top></Top>
		<Dashboard></Dashboard>
	</div>
</template>

<script>
	import Top from '../components/education/Top.vue';
	import Dashboard from '../components/education/Dashboard.vue';
	export default {
		name: 'Education',
		components: {
			Top,
			Dashboard,
		},
		props:{
		},
		created: function(){
			
		}
	};
</script>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Aclonica&display=swap');
	
	html, body {
		margin: 0;
	}
	.college_image{
		width: 100vw;	
		height: 400px;
		position: absolute;
		object-fit: cover;
		z-index: 1;
	}
	
	
	
	
</style>