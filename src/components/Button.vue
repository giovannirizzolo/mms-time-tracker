<template>
	<router-link to="/{{path}}" class="genericButton">{{ title }}</router-link>
</template>

<script>
	export default {
		name: "Button",
		props: {
			title: String,
		},
	};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	.genericButton {
		background-color: #d7282f;
		color: #fff;
		width: 20%;
		height: 14%;
		border-radius: 10px;
		font-family: Gotham;
		display: flex;
		font-size: 32px;
		justify-content: center;
		align-items: center;
	}
</style>
