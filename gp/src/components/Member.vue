<template>
	<li>
		<span>{{ full_name }}</span>
	</li>	
</template>

<script>
export default {
	props: [
		"member"
	],
	computed: {
		full_name: function(){
			return this.member.first_name + " " + this.member.last_name;
		},
	}
}
</script>

