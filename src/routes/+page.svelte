<main>
	<h1>Vanessa et Louis</h1>
	<p>à bientôt</p>
</main>

<style>
	:global(body) {
		margin: 0;
	}

	main {
		min-height: 100vh;
		display: grid;
		place-content: center;
		text-align: center;
		color: white;
		background-image: url('/background.png');
		background-size: cover;
		background-position: center;
		background-repeat: no-repeat;
		padding: 1rem;
	}

	h1 {
		margin: 0;
		font-size: clamp(2rem, 8vw, 5rem);
		font-weight: 700;
		text-shadow: 0 2px 10px rgba(0, 0, 0, 0.6);
	}

	p {
		margin: 0.5rem 0 0;
		font-size: clamp(0.8rem, 2.5vw, 1rem);
		text-transform: lowercase;
		text-shadow: 0 1px 6px rgba(0, 0, 0, 0.6);
	}
</style>
