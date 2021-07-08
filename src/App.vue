<template>
	<div>
		<Header></Header>
		<Navi></Navi>
		<Main></Main>
		<Footer></Footer>
	</div>
</template>

<script>
import Header from './components/Header.vue'
import Navi from './components/Navi.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default({
	name: 'app',
	components: {
		Header,
		Navi,
		Main,
		Footer
	}
})
</script>

<style scoped lang="scss">
@import "./components/common.scss";

a {
	color: $arkw-color;
}

a:hover {
	opacity: 0.7;
}
</style>