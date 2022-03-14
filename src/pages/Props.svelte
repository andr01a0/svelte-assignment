<script>
	import Declaringprops from "../components/Declaringprops.svelte";
	import Defaultvalues from "../components/Defaultvalues.svelte";
	import Spreadprops from "../components/Spreadprops.svelte";
</script>

<main>
	<h1>Props</h1>
	<Declaringprops/>
	<Defaultvalues/>
	<Spreadprops/>
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