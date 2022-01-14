<script>
	import Pix from "./pix.svelte"
</script>

<main>
	<h1>hbd champion!</h1>
	<div class=container>
		<Pix />
		<Pix />
		<Pix />
		<Pix />
		<Pix />
		<Pix />
		<Pix />
		<Pix />
		<Pix />
		<Pix />
		<Pix />
		<Pix />
	</div>
</main>

<style>
	main {
		text-align: center;
		margin: 0;
	}
	h1 {
		color: #ff3e00;
		font-size: 4em;
		font-weight: 100;
		margin: 0;
	}
	.container {
		display: grid;
		grid-template-columns:  1fr 1fr 1fr;
		border: 1px solid red;
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>