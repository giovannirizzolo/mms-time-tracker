<template>
	<Header/>
	<Subheader pageName="Home" />
	<div class="buttons">
		<Button path="" title="New championship" />
		<Button path="race" title="New race" />
		<Button path="race" title="Add driver" />
		<Button path="race" title="Add new car" />
		<Button path="race" title="Add new track" />
	</div>
</template>

<script>
	import Header from "../components/Header.vue";
	import Subheader from "../components/Subheader.vue";
	import Button from "../components/Button.vue";

	export default {
		name: "Home",
		components: {
			Header,
			Subheader,
			Button,
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
