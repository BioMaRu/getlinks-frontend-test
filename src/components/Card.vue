<template>
	<div class="col-xs-12 col-sm-6 col-md-3">
		<div class="card">
			<div class="cover" v-bind:style="{ backgroundImage: 'url('+ coverUrl +')' }"></div>
			<div class="info">
				<a v-bind:href="url"><div class="title">{{ title }}</div></a>
				<div class="caption sub-font">{{ caption }}</div>
			</div>
		</div>

	</div>
</template>

<script>
	
export default {
	data () {
		return {
//			coverUrl: 'http://loremflickr.com/320/240?random=1'
		}
	},
	props: {
		coverUrl: { type: String },
		title: { type: String },
		caption: { type: String },
		url: { type: String }
	},
}
</script>

<style scoped lang="less">
	a {
		text-decoration: none;
	}
	.card {
		border: 1px solid #d4d4d4;
		border-radius: 5px;
		margin-bottom: 20px;
		overflow: hidden;
	}
	.cover {
		background-color: #e5e5b7;
		background-position: center;
		background-size: cover;
		height: 150px;
	}
	.info {
		padding: 16px 8px;;
		.title {
			margin-bottom: 8px;
		}
		.caption {
			
		}
	}
</style>
