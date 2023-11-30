<script>
	const number = 0 // change the number the text will dispaly non
</script>

<main>
	{#if number === 0}
	<p>If Number Zero text will dispaly</p>
	{:else if number > 0}
	<p>The Number is Positive</p>
	{:else if number < 0}
	<p>The Number is Negative</p>
	{:else}
	<p>Not a Number</p>
	{/if}
</main>

<style>


</style>