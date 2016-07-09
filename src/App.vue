<template>
	<top></top>
	<banner></banner>
	<div class="container card-container">
		<card v-for="article in articles"
			:cover-url="article.coverUrl"
			:title="article.title"
			:caption="article.caption"
			:url="article.url"
		></card>
	</div>
	<foot></foot>
</template>

<script>

import Top from './components/Top'
import Banner from './components/Banner'
import Card from './components/Card'
import Foot from './components/Foot'

export default {
	data () {
		return {
			articles: [
				{	
					coverUrl: 'http://loremflickr.com/320/240?random=1',
					title: 'Title',
					caption: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
					url: 'http://www.google.com'
				},
				{	
					coverUrl: 'http://loremflickr.com/320/240?random=2',
					title: 'Title',
					caption: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
					url: 'http://www.google.com'
				},
				{	
					coverUrl: 'http://loremflickr.com/320/240?random=3',
					title: 'Title',
					caption: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
					url: 'http://www.google.com'
				},
				{	
					coverUrl: 'http://loremflickr.com/320/240?random=4',
					title: 'Title',
					caption: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
					url: 'http://www.google.com'
				},
				{	
					coverUrl: 'http://loremflickr.com/320/240?random=5',
					title: 'Title',
					caption: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
					url: 'http://www.google.com'
				},
				{	
					coverUrl: 'http://loremflickr.com/320/240?random=6',
					title: 'Title',
					caption: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
					url: 'http://www.google.com'
				},
				{	
					coverUrl: 'http://loremflickr.com/320/240?random=7',
					title: 'Title',
					caption: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
					url: 'http://www.google.com'
				},
				{	
					coverUrl: 'http://loremflickr.com/320/240?random=8',
					title: 'Title',
					caption: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
					url: 'http://www.google.com'
				}
			]
		}
	},
	components: {
		Top, Banner, Card, Foot
	}
}
</script>

<style>
	html, body {
		font-family: 'Montserrat', sans-serif;
	}
	.sub-font {
		font-family: 'Domine', serif;;
	}
	.card-container {
		padding-top: 30px;
		padding-bottom: 30px;
	}
</style>
