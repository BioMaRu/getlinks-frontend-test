<template>
	<div class="header">
		<div class="container">
			<img src="../assets/avatar.jpg" alt="logo" class="logo">
			<div class="menu-lists">
				<a href="https://th.linkedin.com/in/theerapong-laowrungrat-29482771">
					<div class="menu col-xs-12 col-sm-2 col-sm-offset-2">Connect me</div>
				</a>
				<a href="https://www.facebook.com/bio.color.palette">
					<div class="menu col-xs-12 col-sm-2">Add Me</div>
				</a>
				<a href="mailto:bio.color.palette@gmail.com">
					<div class="menu col-xs-12 col-sm-2">Contact Me</div>
				</a>
				<a href="https://drive.google.com/file/d/0B-eggagCJ5xMbTZTQWkyc1pTbkk/view?usp=sharing">
					<div class="menu col-xs-12 col-sm-2">About Me</div>
				</a>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	
}
</script>


<style scoped lang="less">

	.header {
		position: relative;
		background: white;
		padding: 20px 0;
		text-align: center;
/*		box-shadow: 0 3px 3px #a3a3a3;*/
		z-index: 5;
	}
	.logo {
		width: 70px;
		height: 70px;
		border-radius: 50%;
		margin-bottom: 30px;
	}
	.menu-lists {
		.menu {
			display: inline-block;
			padding: 5px 15px;
			transition: all 0.2s ease-in-out;
		}
	}
	
</style>
