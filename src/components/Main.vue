<template>
	<div>
		<div class="main">
			<div class="main-left">
				<Sidebar></Sidebar>
			</div>
			<div class="main-right">
				<h1 class="heading">トピックス</h1>
			</div>
		</div>
	</div>
</template>

<script>
import Sidebar from './Sidebar.vue'

export default({
	name: 'app',
	components: {
		Sidebar
	}
})
</script>

<style scoped lang="scss">
@import "./common.scss";

.main-left {
	width: 440px;
	float: left;
}

.main-right {
	width: 700px;
	float: right;
}
</style>