<svelte:head>
	<title>Support - WalkSync</title>
	<meta name="description" content="Get help with WalkSync iOS app" />
</svelte:head>

<div class="page">
	<article class="content">
		<a href="/" class="back">&larr; Back</a>

		<h1>Support</h1>
		<p class="subtitle">Need help with WalkSync? We're here for you.</p>

		<section>
			<h2>Contact</h2>
			<p>
				For questions, bug reports, or feature requests, email
				<a href="mailto:justin@justinj.dev">justin@justinj.dev</a>
			</p>
		</section>

		<section>
			<h2>Frequently Asked Questions</h2>

			<div class="faq">
				<h3>How do I connect my treadmill?</h3>
				<p>
					Make sure your WalkingPad is powered on, then tap <strong>Connect</strong> on the Walk tab.
					WalkSync will scan for nearby Bluetooth devices. Tap your treadmill in the list to connect.
				</p>
			</div>

			<div class="faq">
				<h3>Which treadmills are supported?</h3>
				<p>
					WalkSync works with WalkingPad and KingSmith treadmills that use Bluetooth, including models
					with FTMS (Fitness Machine Service) support and the older custom WalkingPad protocol.
				</p>
			</div>

			<div class="faq">
				<h3>My treadmill isn't showing up</h3>
				<p>
					Make sure Bluetooth is enabled in Settings and your treadmill is powered on. Try turning
					the treadmill off and back on, then tap Connect again. WalkSync needs Bluetooth permission
					to discover devices.
				</p>
			</div>

			<div class="faq">
				<h3>How do I sync to Strava?</h3>
				<p>
					Go to Settings and tap <strong>Connect Strava</strong>. After authorizing, your walks will
					automatically sync to Strava when you save them.
				</p>
			</div>

			<div class="faq">
				<h3>My walk didn't sync to Strava</h3>
				<p>
					If you were offline when saving, WalkSync will queue the upload and retry when you're
					back online. Check the History tab for a pending sync badge.
				</p>
			</div>

			<div class="faq">
				<h3>How do I sync to Apple Health?</h3>
				<p>
					Go to Settings and tap <strong>Connect Apple Health</strong>. Once authorized, walks are
					saved to Health automatically when you tap Save.
				</p>
			</div>

			<div class="faq">
				<h3>How do I delete my data?</h3>
				<p>
					Go to Settings and tap <strong>Delete All Data</strong> at the bottom. This removes all
					session history, pending uploads, and disconnects Strava. You can also delete individual
					sessions from the History tab.
				</p>
			</div>
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

	.subtitle {
		color: var(--color-text-muted);
		font-size: 0.95rem;
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

	.faq {
		margin-bottom: 1.5rem;
	}

	h3 {
		font-size: 1rem;
		font-weight: 500;
		margin-bottom: 0.5rem;
	}

	p {
		margin-bottom: 1rem;
	}

	strong {
		font-weight: 500;
	}
</style>
