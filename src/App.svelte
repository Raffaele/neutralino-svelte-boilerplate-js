<script>
	import IntroPanel from './components/intro-panel.svelte';
	import Credits from './components/credits.svelte';
</script>

<main>
	<h1>Neutralino + Svelte boilerplate</h1>
	<section class="images">
		<IntroPanel />
	</section>
	<section>
		To start: open the project with your favourite editor and change the App.svelte file
	</section>
	<section>
		<Credits />
	</section>
</main>
<style>
	main{
		background-color: aliceblue;
		height: 100vh;
	}
	section {
		padding: 0 10%;
		margin-bottom: 50px;
	}
	h1 {
		color: #ff9090;
		text-align: center;
		margin-top: 0;
	}
	.images {
		display: flex;
		justify-content: center;
	}
</style>