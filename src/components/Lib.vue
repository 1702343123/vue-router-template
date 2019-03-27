<template>
	<div class="container">
		<div class="side-bar">
			<router-link to="/lib-one">库分组</router-link>
			<router-link to="/lib-two">题库</router-link>
			<router-link to="/lib-three">库分组</router-link>
			<router-link to="/lib-four">管理</router-link>
		</div>
		<div class="content"><router-view /></div>
	</div>
</template>

<script>
export default {
	name: 'Lib',
	data() {
		return {
			
		};
	}
};
</script>

<style>
	.content{
		/* flex: 1 1 80%; */
		/* text-align: left; */
		background-color: #fff;
		margin-left: 20px;
		padding-bottom: 20px;
	}
</style>
