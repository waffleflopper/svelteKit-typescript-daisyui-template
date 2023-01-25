<script>
	import '../lib/global.css';
	import Navbar from '$lib/components/Navbar.svelte';
</script>

<Navbar />
<div class="app">
	<header />
	<main>
		<slot />
	</main>
</div>

<style>
	.app {
		width: 100%;
		display: flex;
		justify-content: center;
	}
	main {
		position: relative;
		max-width: 80vw;
		min-width: 60vw;
	}
</style>
