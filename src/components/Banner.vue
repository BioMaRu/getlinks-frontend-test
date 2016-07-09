<template>
	<div class="banner">
		<div class="image">
			
		</div>
		<div class="container">
			<h1>Awesome <span class="shake-constant shake-slow">ME!</span></h1>
			<p class="sub-font">I have nothing to say... </p>
			<p class="sub-font">But I have some kitties to show!!</p>
		</div>
	</div>
</template>

<script>
import 'csshake/dist/csshake.min.css'
export default {
	data () {
		return {
			msg: 'Hello World!'
		}
	}
}
</script>

<style scoped lang="less">
	h1 {
		color: white;
		text-shadow: 6px 6px 0px rgba(0, 0, 0, 0.33);
		margin-bottom: 30px;
	}
	p {
		font-size: 1.5em;
		color: white;
		text-shadow: 0px 4px 3px rgba(0,0,0,0.4),
					 0px 8px 13px rgba(0,0,0,0.1),
					 0px 18px 23px rgba(0,0,0,0.1);
	}
	.container {
		position: relative;
		z-index: 5;
		padding-top: 60px;
		padding-bottom: 90px;
	}
	.banner {
		position: relative;
		background: #eaeaea;
/*		height: 300px;*/
		text-align: center;
		background-color: #e5e294;
	}
	.image {
		position: absolute;
		width: 100%;
		height: 100%;
		background-image: url(../assets/banner.jpg);
		background-position: center;
		background-size: cover;
		opacity: 0.3;
	}

</style>
