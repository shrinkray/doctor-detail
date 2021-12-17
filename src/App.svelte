<script lang="ts">
	import ModeSwitcher from './ModeSwitcher.svelte';
	import Tailwindcss from './Tailwindcss.svelte';
	import HeroCardBackground from "./HeroCardBackground.svelte";
	import Navigation from "./Navigation.svelte";
	export let name: string;
</script>
<style>
	.custom-style {
		@apply italic;
	}
</style>
<Tailwindcss />
<ModeSwitcher />

<main class="p-4 mx-auto text-center max-w-full">
	<Navigation />
	<HeroCardBackground />
</main>