<script>
	import { base } from '$app/paths';
</script>

<div class="container">
	<img class="image" src="{base}/images/woooo.gif" alt="" />
</div>

<style>
	.container {
		position: fixed;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
	}

	@media only screen and (max-width: 700px) {
		.image {
			width: 90vw;
		}
		.container {
			width: 90vw;
			padding: 10;
		}
	}
</style>
