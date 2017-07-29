<template>
	<div>
		<div class="header">header</div>
		<div>
			<router-view></router-view>
		</div>
		<div class="footer">footer</div>
	</div>
</template>
<script>
	export default {

	}
</script>
<style>
/* css reset*/
	.header {
		height: 70px;
		background: blue;
	}
	.footer {
		height: 70px;
		background: gray;
		text-align: center;
	}
</style>