<template>
	<section>
		<div class="container">
			<div class="items">
				<div class="item">
					<img  src="../assets/img/buy-comics-digital-comics.png" alt="">
					<h3>digital comics</h3>
				</div>
				<div class="item">
					<img  src="../assets/img/buy-comics-digital-comics.png" alt="">
					<h3>digital comics</h3>
				</div>
				<div class="item">
					<img  src="../assets/img/buy-comics-digital-comics.png" alt="">
					<h3>digital comics</h3>
				</div>
				<div class="item">
					<img  src="../assets/img/buy-comics-digital-comics.png" alt="">
					<h3>digital comics</h3>
				</div>
				<div class="item">
					<img  src="../assets/img/buy-comics-digital-comics.png" alt="">
					<h3>digital comics</h3>
				</div>
				
			</div>
		</div>
	</section>
</template>

<script>
export default {
name:"Vue"
}
</script>

<style lang = "scss" scoped>
	section{
		background: #0282f9;
	}
	.items{
		display: flex;
		justify-content: center;
	}
	.item{
		display: flex;
		align-items: center;
		width: 100% / 5;
		padding: 0 30px;

		img{
			max-width: 55px;
		}
		h3{
			color: #fff;
			padding: 0 0 0 10px;
		}
	}
</style>