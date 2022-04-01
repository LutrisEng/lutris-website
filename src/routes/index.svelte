<script context="module">
	export const prerender = true;
</script>

<script lang="ts">
	import fleetboxscreenshot from '$lib/assets/fleetboxscreenshot.jpeg';
</script>

<header>
	<h1>Lutris, Inc</h1>
	<p>Lutris builds automotive tools and products for businesses and consumers alike.</p>
</header>
<section id="currentproducts">
	<h2>Current Products</h2>
	<section id="fleetbox">
		<h3>Fleetbox (coming soon)</h3>
		<img src={fleetboxscreenshot} alt="A screenshot showing a vehicle in the Fleetbox app" />
		<p>
			Fleetbox is an iOS, iPadOS, and macOS application that helps you track your vehicle's
			maintenance history, and make sure you stay on top of its maintenance requirements.
		</p>
		<p>
			A private beta is starting soon - if you're interested, get in touch at
			<a href="mailto:fleetboxbeta@lutris.engineering">fleetboxbeta@lutris.engineering</a>!
		</p>
	</section>
</section>
<section id="services">
	<h2>Services</h2>
	<section id="customautomotivesoftware">
		<h3>Custom automotive software</h3>
		<p>
			We build custom automotive software for anyone from OEMs to aftermarket equipment
			manufacturers.
		</p>
	</section>
</section>
<footer>
	<hr />
	<p>
		Lutris, Lutris Engineering, and Fleetbox are trademarks of Lutris, Inc, a Texas corporation. All
		rights reserved.
	</p>
	<p>Get in touch at <a href="mailto:contact@lutris.engineering">contact@lutris.engineering</a>!</p>
</footer>

<style>
	img {
		max-width: 25vw;
	}
</style>
