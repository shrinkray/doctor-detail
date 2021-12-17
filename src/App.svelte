<script lang="ts">
	// import ModeSwitcher from './ModeSwitcher.svelte';
	import Tailwindcss from './Tailwindcss.svelte';
	import HeroCardBackground from "./HeroCardBackground.svelte";
	import Navigation from "./Navigation.svelte";
	import Team from "./Team.svelte";
	import Testimonial from "./Testimonial.svelte";
	import CustomerService from "./CustomerService.svelte";
	import Footer from "./Footer.svelte";
</script>

<Tailwindcss />
<!--<ModeSwitcher />-->

<main class="p-4 mx-auto text-center max-w-full">
	<Navigation />
	<HeroCardBackground />
	<CustomerService />
	<Team />
	<Testimonial />
</main>
<Footer />