<script>
	const names = ['KrishnaKumar','Jomon']
	const objectName= [
		{firstName:'Krishna', lastName: 'Kumar'},
		{firstName:'Jomon' , lastName: 'VG'}
	]
	
</script>

<main>
	{#each names as name }
		<p>{name}</p>
	{/each}

	{#each objectName as name }
	<p>{name.firstName} {name.lastName}</p>
		
	{/each}
</main>

<style>


</style>