<template>
	<section>
	<div class="container">
			<div class="items">
				<div v-for = "(item,index) in navItems" :key = 'index' class="item">
					<img  src="../assets/img/buy-comics-digital-comics.png" alt="">
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
				img:"buy-comics-digital-comics.png",
				title:"Digital Comics"
				},
				{
				img:"buy-comics-merchandise.png",
				title:"DC Merchandise"
				},
				{
				img:"buy-comics-subscriptions.png",
				title:"Subscription"
				},
				{
				img:"buy-comics-shop-locator.png",
				title:"Comic Shop Locator"
				},
				{
				img:"buy-dc-power-visa.svg",
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
		padding: 20px;
		& > div{
			display: flex;
			justify-content: center;
		}
	}
	.items{
		display: flex;
		justify-content: center;
		flex-wrap: wrap;
		

	}
	.item{
		display: flex;
		justify-content: center;
		align-items: center;
		padding: 0 20px;
		width: calc(100% / 5);


		img{
			max-width: 50px;
		}
		h3{
			color: #fff;
			padding: 0 0 0 5px;
		}
	}
</style>