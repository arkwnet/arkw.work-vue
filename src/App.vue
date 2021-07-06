<template>
	<div>
		<Header></Header>
	</div>
</template>

<script>
import Header from './components/Header.vue'

export default({
	name: 'app',
	components: {
		Header
	}
})
</script>

<style scoped>
a {
	color: #3f51b5;
}

a:hover {
	opacity: 0.7;
}
</style>