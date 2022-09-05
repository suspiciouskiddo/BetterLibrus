<style>
	.topnavdiv {
		position: absolute;
		top: 0;
		left: 0;
		background-color: rgb(114, 36, 36);

		width: 100%;
		height: 100px;
	}

	h1 {
		color: black;
		padding-top: 5px;
		padding-left: 15px;
	}
	.navelement {
		background-color: red;
		position: relative;
		width: 100px;
		height: 100px;
		
	}
</style>

<main>
	<div class="topnavdiv"> 
		<div><h1>BetterLibrus</h1></div>
		{#if loggedIn}
			<div class="navelement"></div>
		{:else}
		<h2>Zaloguj się, aby zobaczyć więcej</h2>
		{/if}
</div>
	<!-- Zastosować jakiegos flexsboxa czy cos na navbara -->
</main>

<script>
let loggedIn = true;
</script>
