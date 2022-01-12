<template>
	<Home />
</template>

<script>
	import Home from "./pages/Home.vue";

	export default {
		name: "App",
		components: {
			Home,
		},
	};
</script>

<style lang="scss">
	@font-face {
		font-family: Gotham;
		src: url("./assets/fonts/Gotham-Black.otf");
	}
	#app {
		font-family: Gotham, Avenir, Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
	}
</style>
