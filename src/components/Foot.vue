<template>
	<div class="footer-container">
		<div class="container">
			<div class="item col-xs-3 col-md-3">
				<div class="title">My Address</div>
				<div class="info sub-font">1305/88 Wongsawang, Bangsue distric, Bangkok 10800</div>
			</div>
			<div class="item col-xs-12 col-md-3">
				<div class="title">Hobby</div>
				<div class="info sub-font">Gaming, Reading, Eating</div>
			</div>
			<div class="item col-xs-12 col-md-3">
				<div class="title">Love</div>
				<div class="info sub-font">UI Design, UX Design, Human Psychology</div>
			</div>
			<div class="item col-xs-12 col-md-3">
				<div class="title">Kitties</div>
				<div class="pic col-xs-4"><img src="http://loremflickr.com/80/80?random=1"></div>
				<div class="pic col-xs-4"><img src="http://loremflickr.com/80/80?random=2"></div>
				<div class="pic col-xs-4"><img src="http://loremflickr.com/80/80?random=3"></div>
			</div>
		</div>
	</div>
</template>

<script>
	
export default {
	
}
</script>

<style scoped lang="less">
	.item {
		margin-bottom: 20px;
	}
	.footer-container {
		padding: 50px 0;
		background-color: #2e2c25;
		color: white;
		.title {
			color: #e0e0e0;
			font-size: 1.3em;
			margin-bottom: 8px;
		}
		.info {
			color: #e0e0e0;
		}
	}
	.pic {
		padding-left: 0;
		overflow: hidden;
		
		img {
			width: 100%;
			border-radius: 3px;
		}
	}

</style>
