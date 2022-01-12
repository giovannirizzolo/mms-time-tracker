<template>
	<Header />
	<Subheader pageName="Add new driver" />
</template>

<script>
	import Header from "../components/Header.vue";
	import Subheader from "../components/Subheader.vue";
	
	export default {
		name: "Driver",
		components: {
			Header,
			Subheader,
		},
	};
</script>

<style lang="scss">
	.buttons {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-between;
		height: 45%;
		margin-top: 5%;
	}
</style>
