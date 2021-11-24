<template>
	<div class="links-wrapper">
		<div class="container">
			<section>				
				<div class="comics-links">
					<ul>
						<li><h2>Title</h2></li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
					</ul>
						<ul>
						<li><h2>Title</h2></li>
						<li>Characters</li>
						<li>Characters</li>
					</ul>
				</div>
				<div class="comics-links">
					<ul>
						<li><h2>Title</h2></li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
					</ul>
				</div>
				<div class="comics-links">
					<ul>
						<li><h2>Title</h2></li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
						<li>Characters</li>
					</ul>
				</div>	
			</section>
		
		</div>
	</div>	
</template>

<script>
export default {
name:'FooterLinks'
}
</script>

<style lang='scss' scope>
@import '@/styles/variables';

	.links-wrapper{
		background-image: url('../assets/img/footer-bg.jpg');
		background-repeat: no-repeat;
		background-size: cover;
			
			section{
				display: flex;
				background-image: url(../assets/img/dc-logo-bg.png);
				background-repeat: no-repeat;
				background-position: center right;
				background-size:  40%;
					.comics-links{
						padding: 40px 25px  60px 0;
						h2{
							color: $whitheColor;
							font-size: 1rem;
							margin: 0.7rem 0 0.7rem 0;
						}
						li{
							color:$colorLightGray;
							font-size: 0.8rem;
						}
					}
			}
			
	}

</style>