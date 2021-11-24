<template>
	<section>
		<div class="container">
			<div class="sign-up">
				<a href="">Sign Up Now</a>
			</div>
			<div class="social">
				<a href="">Folow Us</a>
				<img src="../assets/img/footer-facebook.png" alt="">
				<img src="../assets/img/footer-periscope.png" alt="">
				<img src="../assets/img/footer-pinterest.png" alt="">
				<img src="../assets/img/footer-twitter.png" alt="">
				<img src="../assets/img/footer-youtube.png" alt="">
			</div>
		</div>
	</section>	
</template>

<script>
export default {
name:'FooterAbout'
}
</script>

<style lang="scss" scoped>
@import '@/styles/variables';

section{
	background-color: $brownColor;
		> div{
			display: flex;
			justify-content: space-between;
			align-items: center;
			padding: 30px 0;
		}
		.sign-up{
			padding: 1rem;
			border: 2px solid $brandColor;
				a{
					color: $whitheColor;
					text-transform: uppercase;
					font-weight: 600;
					

				}

		}
		.social{
			display: flex;
			align-items: center;
			a{
					font-weight: 700;
					color: $brandColor;
					text-transform: uppercase;
					font-size: 1rem;
			}

			img{
				width: 40px;
				padding-left: 18px;
			}
		}

}
</style>

