<script>
	import Introduction from "./pages/Introduction.svelte";
	import Reactivity from "./pages/Reactivity.svelte";
	import Props from "./pages/Props.svelte";
	import Logic from "./pages/Logic.svelte";
	import Events from "./pages/Events.svelte";
	export let name;
</script>

<main>
	<h1>Welcome to {name}!</h1>
	<Introduction/>
	<Reactivity/>
	<Props/>
	<Logic/>
	<Events/>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>