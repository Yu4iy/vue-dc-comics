<template>
	<section>
		<div class="container">

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
				<div class="bg-fot-img">

				</div>
		</div>
	</section>
</template>

<script>
export default {
name:'FooterLinks'
}
</script>

<style lang='scss' scope>


	section{
		background-image: url('../assets/img/footer-bg.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		color: #fff;
		& > div{
			display: flex;
		}
			ul{
				color: rgb(109, 109, 109);
				list-style: none;
				padding: 20px;
			}
		.bg-fot-img{
			background-repeat: no-repeat;
			width: 100%;
			overflow: hidden;
			background-position-x: right;
			background-position-y: center;
			background-image: url('../assets/img/dc-logo-bg.png');
		}
	}

</style>