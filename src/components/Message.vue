<template>
	<div class="alert alert-info custom-alert">
		<strong><slot name="title"></slot></strong>  
		<slot name="body"></slot>
	</div>
</template>

<script>
	
</script>

<style scoped>
	.custom-alert{
		border-color: red;
	}
</style>