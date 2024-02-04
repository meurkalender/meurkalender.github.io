<script lang="ts">
	import { base } from '$app/paths';
</script>

<!-- <meta name="viewport" content="width=device-width, initial-scale=1.0"> -->
<div class="container">
	<div class="infodiv" id="imgid">
		<img class="plaatje" src="{base}/images/meurkalender.png" alt="" />
	</div>
	<div class="infodiv" id="textid">
		<h1>WELKOM!</h1>
		<p>Goed nieuws! De tweede editie van de Meurkalender is uit *!</p>
		<p>Bestel jouw Meurkalender via deze link:</p>
		<div class="linkdiv">
			<a class="link" href="{base}/kopenmaar">ik wil een meurkalender bestellen</a>
		</div>
		<p>Wees snel want de oplage is beperkt! en vergeet niet: Vrijdag Veegdag!</p>
		<p class="kleinelettertjes">
			*Wetenschappelijk onderzoek wijst uit dat de 2e editie 2.34 x hoger scoort kwa humor.
		</p>
	</div>
</div>

<style>
	.container {
		height: 90vh;
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
	}
	/* .container {
		height: 80vh;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	} */
	.infodiv {
		text-align: center;
	}
	#textid {
		text-align: center;
		font-family: 'Avenir Next';
		font-weight: bold;
		font-family: 'AvenirNext-DemiBold';
		color: #943a70;
		width: 50vw;
	}
	.plaatje {
		width: 50vw;
	}
	.link {
	}
	.linkdiv {
		background-color: #fadd4e;
		border: 10px solid #c63026;
		border-radius: 40px;
		padding: 20px;
		text-align: center;
		margin-top: 50px;
		margin-bottom: 50px;
		/* white-space: nowrap; */
		/* white-space: nowrap; */
		/* overflow: hidden; */
		/* text-overflow: ellipsis; */
	}
	.kleinelettertjes {
		font-size: 0.7em;
	}
	@media only screen and (max-width: 700px) {
		.container {
			flex-direction: column;
		}
		.plaatje {
			width: 100vw;
		}
	}
	/* :global(body) {
		margin: 0;
	} */
	/* body,
	html {
		margin: 0;
		padding: 0;
	}
	* {
		box-sizing: border-box;
	} */
</style>
