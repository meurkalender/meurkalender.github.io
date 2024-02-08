<script>
	import { base } from '$app/paths';
</script>

<div class="container">
	<img class="image" src="{base}/images/woooo.gif" alt="" />
</div>
<p>Succes! Je Meurkalender is besteld. En je geld onderweg naar een Zwitserse Bank.</p>

<style>
	.container {
		position: fixed;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
	}
	p {
		height: 90vh;
		display: flex;
		flex-direction: row;
		justify-content: center;
		/* align-items: center; */
		/* margin: auto;
		width: 50%;
		justify-content: center;
		padding: 10px; */
		/* display: flex;
		text-align: center;
		align-items: center; */
		font-family: 'Prompt', sans-serif;
		font-size: 2em;
		color: #b6c9e9;
	}

	@media only screen and (max-width: 700px) {
		.image {
			width: 90vw;
		}
		.container {
			width: 90vw;
			padding: 10;
		}
		p {
			font-size: 1em;
		}
	}
</style>
