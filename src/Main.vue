<template>
	<div>
		<Header></Header>
		<Navi></Navi>
		<Footer></Footer>
	</div>
</template>

<script>
import Header from './components/Header.vue'
import Navi from './components/Navi.vue'
import Footer from './components/Footer.vue'

export default({
	name: 'app',
	components: {
		Header,
		Navi,
		Footer
	}
})
</script>

<style scoped>
@import "./components/common.css";

a {
	color: #3f51b5;
}

a:hover {
	opacity: 0.7;
}
</style>