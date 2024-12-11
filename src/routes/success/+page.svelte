
<script lang="ts">
  import Header from "../_header.svelte";
  import Footer from "../_footer.svelte";
</script>

<Header />
<main class="container">
  <h2>Success!</h2>
	<p>Your request has been successfully posted. A LAHS Hack Club representative will reach out to you shortly.</p>
	<p>Thanks for reaching out! <a href="/">Return to the main page.</a></p>
</main>
<Footer />

<style>
	.container {
		min-height: calc(100vh - 600px);
	}
	h2 {
		font-size: 4rem;
		border-bottom: 5px solid #3344BB;
	}
</style>