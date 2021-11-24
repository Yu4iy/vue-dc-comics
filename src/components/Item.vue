<template>
 <div>
		<img :src="img" alt="">
		<h3>{{title}}</h3> 
 </div>
</template>

<script>

export default {
name:'Item',
props:{
	img: String,
	title: String,
}
}
</script>

<style lang="scss" scoped>
@import '@/styles/variables';

			h3{
				margin: 1rem 0 0 0;
				color: $whitheColor;
			}
</style>>

