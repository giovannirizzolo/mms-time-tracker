<template>
	<div class="mainBar">
		<img src="../assets/MMS_logo.svg" alt="" class="mainBar__logo" />
    <h1 class="mainBar__title">Simulator Time Tracker</h1>
	</div>
</template>

<script>
	export default {
		name: "Header",
	};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	.mainBar{
    height: 15%;
    width: 100%;    
    background-color: #000;
    display: flex;
    justify-content: center;
    align-items: center;
    img{
      // max-height: 100%;
      width: 50px;
      height: 50px;
    }
    h1{
      font-size: 32px;
      color: #fff;
    }
    img, h1{
      margin: 5px;
    }
  }
</style>
