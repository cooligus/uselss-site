<script>
	import Button from './components/Button.svelte';
	import Card from './components/Card.svelte';
	import Footer from './components/Footer.svelte';
	import InlineCard from './components/InlineCard.svelte';
	import Jumbotron from './components/Jumbotron.svelte';
	import './page.css';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="global-container">
	<nav class="sidebar">
		<img src="https://baconmockup.com/90/100" alt="" />
		<h1>Simple page</h1>
		<hr />
		<Card />
		<Card />
		<hr />
		<InlineCard />
		<hr class="light-divider" />
		<InlineCard />
		<hr class="light-divider" />
		<InlineCard />
		<hr class="light-divider" />
		<InlineCard />
		<hr class="light-divider" />
		<InlineCard />
		<hr />
		<article>
			<h2>Title</h2>
			<p>LOrem ipsum random text</p>
		</article>
		<Button>Learn more</Button>
		<hr />

		<Footer />
	</nav>
	<main class="main-content">
		<Jumbotron />
		<Jumbotron />
		<div class="inliner">
		<Button>Previous page</Button>
		<Button>Next page</Button>
		</div>
	</main>
</section>
