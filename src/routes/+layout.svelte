<script lang="ts">
	import '../app.css';
	import Navbar from '../components/Navbar.svelte';

	let scrollY: number;
</script>

<svelte:window bind:scrollY />

<div>
	<Navbar {scrollY} />
	<main class="mt-20 overflow-y-scroll mb-14 text-slate-800">
		<slot />
	</main>
</div>
