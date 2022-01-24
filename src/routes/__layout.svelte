<script>
	import Header from '$lib/header/Header.svelte';
	import Triangle from '$lib/Triangle.svelte';
	import '../app.css';
</script>

<nav class="h-screen">
	<section class="bg-gradient-to-b from-[#f9b133] to-[#e6037a] h-screen pt-6">
		<a
			class="hover:text-opacity-100 cursor-pointer block text-4xl text-right pr-8 mb-6 text-white text-opacity-80"
			>About</a
		>
		<a
			class="hover:text-opacity-0  cursor-pointer block text-4xl text-right pr-8 mb-6 text-white text-opacity-80"
			>Stations</a
		>
		<a
			class="hover:text-opacity-100  cursor-pointer block text-4xl text-right pr-8 mb-6 text-white text-opacity-80"
			>Chart Show</a
		>
	</section>
	<div class="fixed h-full w-3 bg-opacity-75 bg-white right-0 top-0 z-20" />
</nav>
<main>
	<slot />
</main>

<footer>
	<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
</footer>

<style>
</style>
