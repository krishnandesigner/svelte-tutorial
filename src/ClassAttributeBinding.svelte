<script>
	const status ="green" // change class name here
	const ifConditon=true // change true or flase
	const classNameSameVariableName=true
</script>

<main class="classBinding">
	<div class="fontColor">Div is come form dynamic</div>
	<div class={status}>Change div color based on status value</div>
	<div class={ifConditon ? 'textBold' : ''}>Change div class based on condition</div>
	<div class:textBold={ifConditon}>Change div class based on condition</div>
	<div class:classNameSameVariableName>Class Name and Variable Name are same use short hand code</div>
	

</main>

<style>

.fontColor{
	color:blue;
}
.green{
	color: green;
}
.red{
	color: red;
}

.textBold{
	font-weight: bold;
}
.classNameSameVariableName{
	font-weight: bold;
}
</style>