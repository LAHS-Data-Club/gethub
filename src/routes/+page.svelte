<script lang="ts">
	import Header from './_header.svelte';
	import Footer from './_footer.svelte';
</script>

<Header />
<main class="container">
	<h2>Free Websites for Clubs</h2>
	<p>
		The Los Altos High School Data Club is running an interest program for clubs to having free and
		easy web presence. This program will provide a <b>free lahs.club</b> domain, which you can have redirect
		to your club's website, Instagram, or another page. It's memorable and great for promoting on social
		media or on posters! We will offer a variety of options and support for every club, whether you have
		a website already or not.
	</p>
	<br />
	<h2>Flexible Options</h2>
	<p>New to GEThub, we have options to meet your club wherever you are at.</p>
	<div class="flex-smart cards">
		<div class="flex">
			<h3>Keep Your Site</h3>
			<p>
				Keep your existing Google, Wix, or other site and get a <b>free lahs.club domain</b> as a fast
				shortcut.
			</p>
		</div>
		<div class="flex">
			<h3>Make a New Site</h3>
			<p>Learn to make and manage a new site without any code!</p>
		</div>
		<div class="flex">
			<h3>Custom</h3>
			<p>Need more, or already have code to deploy? We can help!</p>
		</div>
	</div>
	<br />
	<h2>Requirements</h2>
	<p>
		To request a site or a domain, you must be the acting president of the club in question <b
			>and</b
		> must have your club advisor's approval. You agree that any info published on your club's site reflects
		the MVLA school district as a whole.
	</p>
	<br />
	<p class="cta">
		<a href="https://forms.gle/EoFwkLXPAEptgkus7">Show interest in LAHS GEThub ></a>
	</p>
</main>
<Footer />

<style>
	a {
		text-decoration-color: #fffa;
	}
	h2,
	h3 {
		font-weight: 500;
		margin-top: 15px;
		margin-bottom: 6px;
	}
	h2 {
		background-color: #34b;
		border-radius: 5px;
		color: #fff;
		font-size: 1.4rem;
		max-width: fit-content;
		margin-top: 50px;
		margin-bottom: 15px;
		padding: 5px 20px;
	}
	h3 {
		font-size: 1.3rem;
	}
	p {
		font-size: 1rem;
		font-weight: 300;
		margin: 0;
		margin-top: 5px;
	}
	.cta {
		border: 5px solid #34b;
		border-radius: 10px;
		font-weight: 500;
		font-size: 1.2rem;
		margin: 50px 0;
		margin-bottom: 0;
		padding: 15px 20px;
		width: fit-content;
		transition-duration: 0.2s;
		background-color: #fffa;
		box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
	}
	.cta:hover {
		background-color: #34b;
		color: #fff;
		transform: scale(1.05);
	}
	.cta a {
		color: #34b;
		padding: 25px 30px;
		text-decoration: none;
	}
	.cta:hover a {
		color: #fff;
	}
	.cta:hover a {
		color: #fff;
	}
	.cards {
		column-gap: 20px;
		row-gap: 20px;
		margin-top: 20px;
	}
	.cards h3 {
		margin-top: 0;
	}
	.cards > * {
		border: 2px solid #aaf;
		border-radius: 5px;
		padding: 20px;
	}
</style>
