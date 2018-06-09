<template>
	<div>
		<ul>
			<member v-for="member in members" :member="member"></member>
		</ul>
	</div>
</template>

<script>
import Member from './Member.vue';

export default {
	props: [
		"members"
	],
	data: function(){
		return {

		};
	},
	components: {
		Member
	},
	created: function(){
		console.log("Hola que tal");
	},
}
</script>