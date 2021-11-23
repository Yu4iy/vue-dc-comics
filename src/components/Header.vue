<template>
	<header>
		<div class="container">
			<img src="../assets/img/dc-logo.png" alt="">
			<ul>
				<li v-for = "(link,index) in links"
				:key="index"
				>
				<a href="">{{link}}</a>

				</li>
				
			</ul>
		</div>
	</header>
</template>

<script>
export default {
	name:'Header',
	data() {
	return {
		links: 
			[
				"characters",
				"comics",
				"movies",
				"tv",
				"games",
				"collectibles",
				"videos",
				"fans",
				"news",
				"shop",
			],
		}
	}
}

</script>

<style lang = 'scss' scope >
	header{
		padding: 20px 0;
		ul{
			list-style: none;
			display: flex;
			li{
				padding-right: 30px;
				position: relative;
				text-transform: uppercase;
				
				&:last-child{
					padding-right: 0;
				}
				a{
					color:#464652;
					&:hover{
						color: #5382f9;
					}
				}
			}
		}
		div{
			display: flex;
			align-items: center;
			justify-content: space-between;
		}
		img{
			height: 80px;
			width: 80px;
		}

	}
</style>