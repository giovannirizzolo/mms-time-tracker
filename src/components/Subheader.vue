<template>
	<h1 class="subHeader__pageName">
		{{ pageName }}
	</h1>
</template>

<script>
	export default {
		name: "Subheader",
		props: {
			pageName: String,
		},
	};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	h1 {
		color: #000;
	}
</style>
