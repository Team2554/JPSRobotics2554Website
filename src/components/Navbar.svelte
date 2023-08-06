<script lang="ts">
	import { page } from '$app/stores';

	export let scrollY: number;
</script>

<nav
	class={`py-3 px-10 fixed w-full top-0 border-zinc-300 select-none flex justify-between items-center bg-zinc-800 z-50 ${
		scrollY > 20 ? 'border-b-4' : 'border-b-0'
	}`}
>
	<a href="/"><img src="/2554-logo.png" class="cursor-pointer" alt="Team 2554" width="150" /></a>
	<div class="text-lg font-semibold text-white mr-8 flex flex-row space-x-5 uppercase">
		<a class="nav-item" href="/about">About</a>
		<a class="nav-item" href="/executive-board">Executive Board</a>
		<a class="nav-item" href="/sponsors">Sponsors</a>
		<a class="nav-item" href="/gallery">Gallery</a>
		<a class="nav-item" href="/press">Press</a>
		<a class="nav-item" href="/info">Info</a>
	</div>
</nav>

<style lang="postcss">
	.nav-item {
		@apply border-2 hover:border-white border-zinc-800 px-2 py-1 rounded cursor-pointer duration-75;
	}
</style>
