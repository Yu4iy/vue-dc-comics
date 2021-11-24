<template>
	<section>
	<div class="container">
			<div class="items">
				<div v-for = "(item,index) in navItems" :key = 'index' class="item">
					<img  :src = "item.img" alt="">
					<h3>{{item.title}}</h3>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
name:"Vue",
data() {
	return {
		navItems: 
			[
				{
				img:require('../assets/img/buy-comics-digital-comics.png'),
				title:"Digital Comics"
				},
				{
				img:require('../assets/img/buy-comics-merchandise.png'),
				title:"DC Merchandise"
				},
				{
				img:require('../assets/img/buy-comics-subscriptions.png'),
				title:"Subscription"
				},
				{
				img:require('../assets/img/buy-comics-shop-locator.png'),
				title:"Comic Shop Locator"
				},
				{
				img:require('../assets/img/buy-dc-power-visa.svg'),
				title:"DC Power Visa"
				},
			],
		}
	}

}
</script>

<style lang = "scss" scoped>
@import '@/styles/variables';

	section{
		background: $brandColor;
		padding: 50px;

		.items{
			width: 100%;
			display: flex;
			justify-content: space-between;
			padding: 0 30px;

			.item{
				display: flex;
				align-items: center;
				img{
					height: 55px					
				}
				h3{
					font-size: 10px;
					margin-left: 15px;
				}
			}
		}
	}
</style>