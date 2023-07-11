<script>
	import Footer from "./Footer.svelte";
	import "./styles.scss";
</script>

<div class="app">
	<div class="background">
		<div class="numbers">25 + 25 + 10 = 60</div>
		<span />
		<span />
		<span />
		<span />
		<span />
		<span />
		<span />
	</div>

	<!-- <Header /> -->
	<slot />
	<Footer />
</div>

<style lang="scss">
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}
</style>
