
<script lang="ts">
  import Header from "../_header.svelte";
  import Footer from "../_footer.svelte";
</script>

<Header />
<main class="container">
  <h2>Submit a Help Request</h2>
	<p>If you are already part of LAHS GET and need to request help for a change to your website, or if you have general inquiries, please use this form. We respond to the email included as soon as possible.</p>
  <form action="/help" method="post">
		<label for="name">Your Name:</label>
		<input id="name" name="name" type="text" placeholder="First, Last" required>
		<label for="email">Your Email:</label>
		<input id="email" name="email" type="email" placeholder="example@lahs.club" required>
		<label for="club">The organization you represent:</label>
		<input id="club" name="club" type="text" placeholder="e.g. LAHS Hack Club, LAHS, etc." required>
		<label for="club">Your role in the club:</label>
		<input id="club" name="role" type="text" placeholder="e.g. President, Tech Officer, Teacher Advisor, etc." required>
		<label for="req">Message:</label>
		<textarea name="req" id="req" cols="30" rows="10" placeholder="Type your message here..." required></textarea>
		<button type="submit">Submit</button>
	</form>
</main>
<Footer />

<style>
  a {
    text-decoration-color: #fffa;
  }
  h2, h3, h4 {
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

	form {
		display: flex;
		flex-direction: column;
		font-size: 1.3rem;
		margin-top: 30px;
	}
	label {
		margin-bottom: 5px;
	}
	input, textarea {
		border: 1px solid #34b;
		border-radius: 5px;
		margin-bottom: 20px;
		padding: 10px 20px;
		font-family: inherit;
		font-size: 1rem;
	}
	textarea {
		padding: 20px;
	}
  button {
		background-color: #f37;
    border: 5px solid #f37;
    border-radius: 10px;
		color: #fff;
		cursor: pointer;
    font-weight: 500;
    font-size: 1.3rem;
    margin-bottom: 70px;
    padding: 15px 20px;
  }
</style>