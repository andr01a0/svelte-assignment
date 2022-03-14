<script>
	import Ifblocks from "../components/Ifblocks.svelte";
	import Elseblocks from "../components/Elseblocks.svelte";
	import Elseifblocks from "../components/Elseifblocks.svelte";
	import Eachblocks from "../components/Eachblocks.svelte";
	import Keyedeachblocks from "../components/Keyedeachblocks.svelte";
</script>

<main>
	<h1>Logic</h1>
	<Ifblocks/><br/>
	<Elseblocks/>
	<Elseifblocks/>
	<Eachblocks/>
	<Keyedeachblocks/>
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