<script>
	import Pix from "./pix.svelte"
	let pixs = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]
</script>

<main>
	<h1>hbd champion!</h1>
	<div class=container>
		{#each pixs as pix}
			<Pix />
		{/each}
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
		grid-template-columns:  1fr 1fr 1fr 1fr 1fr;
		border: 1px solid red;
		max-height: 80%;
	}
	@media (max-width: 640px) {
		.container{
			grid-template-columns:  1fr 1fr 1fr;
		}
	}
</style>