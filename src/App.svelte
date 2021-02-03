<script>
	export let lærer = "Johan";
	export let elev = "Petter Smart";
</script>

<main>
	<h1>Hei {elev}!</h1>
	<p>Når skal {lærer} hjelpe deg å lære deg Svelte.</p>
</main>

<footer>
	Besøk <a href="https://svelte.dev/tutorial">Svelte tutorial</a> for å bli kjent med <i>Svelte</i>.
</footer>

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