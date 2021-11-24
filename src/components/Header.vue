<template>
	<header>
		<div class="container">
			<img src="../assets/img/dc-logo.png" alt="">
			<ul>
				<li  v-for = "(link,index) in links"
				:key="index"
				>
				<a :class="{active: index === 1}" href="">{{link}}</a>

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
@import '@/styles/variables';

	header{
		padding: 20px 0;
		
		& > div{
			display: flex;
			align-items: center;
			justify-content: space-between;
			
			img{
				max-width: 80px;
			}
		}

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
					color: $brandColor;
					position: relative;
					&:hover{
						color: $brandColor;
					}
				
				}
			}
		}
		

	}
	
	.active::after{
						content: '';
						background: $brandColor;
						height: 5px;
						width: 100%;
						position: absolute;
						bottom: -290%;
						left: 50%;
						transform: translateX(-50%);
					}
	
</style>