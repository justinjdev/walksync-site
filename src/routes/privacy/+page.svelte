<svelte:head>
	<title>Privacy Policy - WalkSync</title>
	<meta name="description" content="Privacy Policy for WalkSync iOS app" />
</svelte:head>

<div class="page">
	<article class="content">
		<a href="/" class="back">&larr; Back</a>

		<h1>Privacy Policy</h1>
		<p class="updated">Last updated: February 2026</p>

		<section>
			<h2>Overview</h2>
			<p>
				WalkSync is a personal fitness app that connects to WalkingPad treadmills via Bluetooth
				and optionally syncs walking sessions to Strava. Your privacy is important, and this
				policy explains what data we collect and how it's used.
			</p>
		</section>

		<section>
			<h2>Data We Collect</h2>

			<h3>Walking Session Data</h3>
			<p>When you use WalkSync, the app collects:</p>
			<ul>
				<li>Duration of your walking sessions</li>
				<li>Distance traveled</li>
				<li>Walking speed</li>
				<li>Session start and end times</li>
			</ul>
			<p>This data is stored locally on your device and is not transmitted to any server unless you choose to sync to Strava.</p>

			<h3>Bluetooth Data</h3>
			<p>
				WalkSync connects to your WalkingPad treadmill via Bluetooth Low Energy (BLE) to read
				real-time walking data. No Bluetooth data is stored or transmitted beyond what's needed
				to display your current session.
			</p>

			<h3>Strava Integration</h3>
			<p>If you choose to connect your Strava account:</p>
			<ul>
				<li>We store OAuth tokens securely in your device's Keychain</li>
				<li>Walking sessions are uploaded to Strava only when you tap "Sync to Strava"</li>
				<li>We request only the minimum permission needed: activity:write</li>
			</ul>
		</section>

		<section>
			<h2>Data Storage</h2>
			<ul>
				<li><strong>Session history:</strong> Stored locally on your device</li>
				<li><strong>Strava credentials:</strong> Stored in iOS Keychain (encrypted)</li>
				<li><strong>No cloud storage:</strong> We do not operate any servers or cloud services</li>
			</ul>
		</section>

		<section>
			<h2>Third-Party Services</h2>
			<p>
				WalkSync integrates with Strava. When you sync activities, your data is subject to
				<a href="https://www.strava.com/legal/privacy" target="_blank" rel="noopener">Strava's Privacy Policy</a>.
			</p>
		</section>

		<section>
			<h2>Data Sharing</h2>
			<p>We do not sell, rent, or share your personal data with anyone. Your walking data stays on your device unless you explicitly sync it to Strava.</p>
		</section>

		<section>
			<h2>Your Rights</h2>
			<p>You can:</p>
			<ul>
				<li>Delete the app to remove all local data</li>
				<li>Disconnect Strava at any time in Settings</li>
				<li>Delete individual sessions from your history</li>
			</ul>
		</section>

		<section>
			<h2>Contact</h2>
			<p>
				Questions about this policy? Contact me at
				<a href="mailto:walksync@justinj.dev">walksync@justinj.dev</a>
			</p>
		</section>
	</article>
</div>

<style>
	.page {
		min-height: 100vh;
		padding: 2rem;
	}

	.content {
		max-width: 650px;
		margin: 0 auto;
	}

	.back {
		display: inline-block;
		color: var(--color-text-muted);
		font-size: 0.9rem;
		margin-bottom: 2rem;
	}

	.back:hover {
		color: var(--color-accent);
	}

	h1 {
		font-size: 2rem;
		font-weight: 600;
		margin-bottom: 0.25rem;
	}

	.updated {
		color: var(--color-text-muted);
		font-size: 0.85rem;
		margin-bottom: 2.5rem;
	}

	section {
		margin-bottom: 2rem;
	}

	h2 {
		font-size: 1.25rem;
		font-weight: 600;
		margin-bottom: 0.75rem;
		color: var(--color-accent);
	}

	h3 {
		font-size: 1rem;
		font-weight: 500;
		margin-top: 1.25rem;
		margin-bottom: 0.5rem;
	}

	p {
		margin-bottom: 1rem;
	}

	ul {
		margin-left: 1.5rem;
		margin-bottom: 1rem;
	}

	li {
		margin-bottom: 0.5rem;
	}

	strong {
		font-weight: 500;
	}
</style>
