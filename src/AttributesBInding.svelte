<script>
	import { Body } from 'svelte-body';
	const divId='divIDName'
	const disabled=true
</script>
<Body class="attribute" />
<main>
	<div id="{divId}">Div is come form dynamic</div>
	<button disabled={disabled}>Boolean Value</button>
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