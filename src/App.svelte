<script>
	const name ="Krishnakumar"
	import Htmlprefix from "./htmlprefix.svelte";
	import Attributes from "./AttributesBInding.svelte";
	import ClassAttributeBinding from "./ClassAttributeBinding.svelte";
	import Condition from "./Condition.svelte";
	import EachBlockList from "./EachBlockList.svelte";
</script>

<main>
	{name}
	<Htmlprefix/>
<Attributes/>
<ClassAttributeBinding/> 
<Condition/>
<EachBlockList/>
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