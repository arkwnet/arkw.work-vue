<template>
	<div>
		<div class="header">
			<div class="wrapper">
				<img src="../assets/logo.svg">
			</div>
		</div>
	</div>
</template>

<style scoped lang="scss">
@import "./common.scss";

.header {
	padding-top: 20px;
	padding-bottom: 8px;
	padding-left: 40px;
	padding-right: 40px;
	position: relative;
	z-index: 100;
	background-color: $arkw-color;
	img {
		height: 60px;
	}
}
</style>