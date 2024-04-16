<script>
	function handleDateChange(event) {selectedDate.set (event.target.value);}
</script>

<main>
	<h1>Форма с выбором даты:</h1>
	<form>
<label for="datePicker">Выберите
дату: </label>
<input type="date" id="datePicker"/>
</form>

</main>	


<style>
	form{
		margin-bottom: 20px;
	}
	label{
		font-weight: bold;
	}
</style>