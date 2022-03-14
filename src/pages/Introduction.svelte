<script>
	import Helloworld from "../components/Helloworld.svelte";
	import Dynamicattributes from "../components/Dynamicattributes.svelte";
	import Styling from "../components/Styling.svelte";
	import Nestedcomponents from "../components/Nestedcomponents.svelte";
	import Htmltags from "../components/Htmltags.svelte";
</script>

<main>
	<h1>Introduction</h1>
	<Helloworld/>
	<Dynamicattributes/>
	<Styling/>
	<Nestedcomponents/>
	<Htmltags/>
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