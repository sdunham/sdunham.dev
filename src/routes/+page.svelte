<script lang="ts">
	// Placeholder website for Scott Dunham
</script>

<main>
	<div class="container">
		<header>
			<h1>Scott Dunham</h1>
			<p class="subtitle">Web Developer</p>
		</header>

		<section class="content">
			<p>
				I'm a web developer based in Tacoma, WA, working at 
				<a href="https://www.sitecrafting.com/team/scott-dunham/" target="_blank" rel="noopener noreferrer">
					SiteCrafting
				</a>.
			</p>

			<p class="note">
				Like many developers, my personal website has been neglected. 
				This placeholder is a gentle reminder that I should probably do something about that.
			</p>

			<div class="contact">
				<p>Get in touch: <a href="mailto:dunham.scott@gmail.com">dunham.scott@gmail.com</a></p>
			</div>
		</section>
	</div>
</main>

<style>
	:global(body) {
		margin: 0;
		padding: 0;
		font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
		line-height: 1.6;
		color: #333;
		background: #f8f9fa;
	}

	main {
		min-height: 100vh;
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 2rem;
	}

	.container {
		max-width: 600px;
		width: 100%;
		background: white;
		padding: 3rem;
		border-radius: 8px;
		box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
	}

	header {
		text-align: center;
		margin-bottom: 2.5rem;
		padding-bottom: 2rem;
		border-bottom: 1px solid #e9ecef;
	}

	h1 {
		margin: 0 0 0.5rem 0;
		font-size: 2.5rem;
		font-weight: 600;
		color: #1a1a1a;
	}

	.subtitle {
		margin: 0;
		font-size: 1.125rem;
		color: #6c757d;
		font-weight: 400;
	}

	.content {
		font-size: 1.125rem;
	}

	.content p {
		margin: 0 0 1.5rem 0;
	}

	.note {
		color: #6c757d;
		font-style: italic;
		font-size: 1rem;
	}

	.contact {
		margin-top: 2.5rem;
		padding-top: 2rem;
		border-top: 1px solid #e9ecef;
		text-align: center;
	}

	.contact p {
		margin: 0;
	}

	a {
		color: #0066cc;
		text-decoration: none;
		transition: color 0.2s ease;
	}

	a:hover {
		color: #0052a3;
		text-decoration: underline;
	}

	@media (max-width: 768px) {
		.container {
			padding: 2rem;
		}

		h1 {
			font-size: 2rem;
		}

		.content {
			font-size: 1rem;
		}
	}
</style>
