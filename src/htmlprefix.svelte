<script>
	import { Body } from 'svelte-body';
	const link='<a href="https://svelte.dev/tutorial">Svelte tutorial</a>'
	let classes = 'teal';
</script>


<Body class="prifix" />

<main>
	
	<b>Normal:</b> {link}
	<br/>
	<b>Add html Prefix (@html):</b> {@html link}
</main>
<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
body{
	background-color: red;
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