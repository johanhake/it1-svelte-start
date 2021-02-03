<script>
	let lærer = "Johan";
	let elev = "Petter Smart";
</script>

<main>
	<h1>Hei {elev}!</h1>
	<p>Nå skal {lærer} hjelpe deg å lære deg lage fete nettsider i Svelte.</p>
	<img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Svelte_Logo.svg" alt="">
</main>

<footer>
	Besøk <a href="https://svelte.dev/tutorial">Svelte tutorial</a> for å bli kjent med <i>Svelte</i>.
</footer>

<style>
	main, footer{
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	main img{
		width: 240px;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main, footer {
			max-width: none;
		}
	}
</style>