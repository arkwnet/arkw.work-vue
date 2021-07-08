<template>
	<div>
		<div class="main">
			<div class="main-left">
				<h1 class="heading">製品情報</h1>
			</div>
			<div class="main-right">
				<h1 class="heading">トピックス</h1>
			</div>
		</div>
	</div>
</template>

<style scoped lang="scss">
@import "./common.scss";

.main {
	width: 1200px;
	margin: auto;
	padding: 20px 5px;
	overflow: hidden;
	box-sizing: border-box;
	h1 {
		padding-top: 20px;
		padding-bottom: 5px;
		font-size: 26px;
		font-weight: normal;
		&.heading {
			padding-top: 20px;
			color: $arkw-color;
			overflow: hidden;
		}
	}
	p {
		padding: 5px 0;
	}
}

.main-left {
	width: 440px;
	float: left;
}

.main-right {
	width: 700px;
	float: right;
}
</style>