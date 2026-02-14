<svelte:head>
	<title>WalkSync</title>
	<meta name="description" content="WalkSync - Track your WalkingPad sessions and sync to Strava" />
</svelte:head>

<div class="page">
	<div class="content">
		<h1>WalkSync</h1>
		<p class="tagline">Track your WalkingPad sessions. Sync to Strava.</p>

		<nav>
			<a href="/privacy">Privacy Policy</a>
			<a href="/terms">Terms of Service</a>
		</nav>

		<p class="footer">
			A personal project by <a href="https://justinj.dev">Justin Jones</a>
		</p>
	</div>
</div>

<style>
	.page {
		min-height: 100vh;
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 2rem;
	}

	.content {
		text-align: center;
		max-width: 400px;
	}

	h1 {
		font-size: 2.5rem;
		font-weight: 600;
		margin-bottom: 0.5rem;
		background: linear-gradient(135deg, #f97316, #fb923c);
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-clip: text;
	}

	.tagline {
		color: var(--color-text-muted);
		margin-bottom: 2rem;
	}

	nav {
		display: flex;
		gap: 2rem;
		justify-content: center;
		margin-bottom: 3rem;
	}

	nav a {
		color: var(--color-text);
		font-size: 0.9rem;
	}

	nav a:hover {
		color: var(--color-accent);
	}

	.footer {
		font-size: 0.85rem;
		color: var(--color-text-muted);
	}
</style>
