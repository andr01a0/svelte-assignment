<script>
	import Domevents from "../components/Domevents.svelte";
	import Inlinehandlers from "../components/Inlinehandlers.svelte";
	import Eventmodifiers from "../components/Eventmodifiers.svelte";
	import Componentevents from "../components/Componentevents.svelte";
	import Eventforwarding from "../components/Eventforwarding.svelte";
</script>

<main>
	<h1>Events</h1>
	<Domevents/>
	<Inlinehandlers/>
	<Eventmodifiers/><br/>
	<Componentevents/><br/>
	<Eventforwarding/>
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