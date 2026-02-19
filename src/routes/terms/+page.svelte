<svelte:head>
	<title>Terms of Service - WalkSync</title>
	<meta name="description" content="Terms of Service for WalkSync iOS app" />
</svelte:head>

<div class="page">
	<article class="content">
		<a href="/" class="back">&larr; Back</a>

		<h1>Terms of Service</h1>
		<p class="updated">Last updated: February 2026</p>

		<section>
			<h2>Acceptance of Terms</h2>
			<p>
				By downloading or using WalkSync, you agree to these Terms of Service. If you do not
				agree, do not use the app.
			</p>
		</section>

		<section>
			<h2>Description of Service</h2>
			<p>
				WalkSync is a free iOS application that connects to WalkingPad treadmills via Bluetooth
				to track walking sessions and optionally sync them to Strava.
			</p>
		</section>

		<section>
			<h2>Use of the App</h2>
			<p>You agree to:</p>
			<ul>
				<li>Use the app only for its intended purpose of tracking walking sessions</li>
				<li>Provide accurate information when connecting to third-party services</li>
				<li>Not attempt to reverse engineer or modify the app</li>
			</ul>
		</section>

		<section>
			<h2>Third-Party Services</h2>
			<p>
				WalkSync integrates with Strava and Apple Health. Your use of these features is subject to
				<a href="https://www.strava.com/legal/terms" target="_blank" rel="noopener">Strava's Terms of Service</a>
				and <a href="https://www.apple.com/legal/internet-services/itunes/" target="_blank" rel="noopener">Apple's Terms of Service</a>.
				We are not responsible for third-party service availability or data handling.
			</p>
		</section>

		<section>
			<h2>Disclaimer of Warranties</h2>
			<p>
				WalkSync is provided "as is" without warranties of any kind. We do not guarantee that:
			</p>
			<ul>
				<li>The app will be error-free or uninterrupted</li>
				<li>Walking data will be 100% accurate</li>
				<li>The app will be compatible with all WalkingPad models</li>
			</ul>
		</section>

		<section>
			<h2>Limitation of Liability</h2>
			<p>
				To the maximum extent permitted by law, we shall not be liable for any indirect,
				incidental, or consequential damages arising from your use of WalkSync, including but
				not limited to lost data or fitness tracking inaccuracies.
			</p>
		</section>

		<section>
			<h2>Health Disclaimer</h2>
			<p>
				WalkSync is not a medical device. Always consult a healthcare professional before
				starting any exercise program. Do not rely on this app for health decisions.
			</p>
		</section>

		<section>
			<h2>Changes to Terms</h2>
			<p>
				We may update these terms at any time. Continued use of the app after changes
				constitutes acceptance of the new terms.
			</p>
		</section>

		<section>
			<h2>Contact</h2>
			<p>
				Questions about these terms? Contact me at
				<a href="mailto:justin@justinj.dev">justin@justinj.dev</a>
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
</style>
