<script lang="ts">
	import { base } from '$app/paths';
	import '@fontsource/roboto';
</script>

<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<div class="container">
	<div class="infodiv" id="imgid">
		<img class="plaatje" src="{base}/images/meurkalender.png" alt="" />
	</div>
	<div class="infodiv" id="textid">
		<h1>WELKOM!</h1>
		<p>Goed nieuws! De tweede editie van de Meurkalender is uit *!</p>
		<p style="font-style:italic">Dé kalender van 1 April 2024 - 1 April 2025</p>
		<p>Bestel jouw Meurkalender via deze link:</p>
		<div class="linkdiv">
			<a class="link" href="https://buy.stripe.com/fZeeVl3HJ1wx7HWbII"
				>ik wil een meurkalender bestellen</a
			>
		</div>
		<p>Na bestelling wordt de kalender eind Maart thuisbezorgd. Afhalen is ook een optie!</p>
		<p>
			Wees <span style="text-decoration:underline">snel</span> want de oplage is beperkt! en vergeet
			niet: Maandag Moonday!
		</p>
		<p class="kleinelettertjes">
			*Wetenschappelijk onderzoek wijst uit dat de 2e editie 2.34 x hoger scoort kwa humor.
		</p>
	</div>
</div>

<!-- how to https://jsfiddle.net/sFM7C/287/ -->
<!-- do cname stuff https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site -->
<!-- get font from open dinges https://khromov.se/adding-locally-hosted-google-fonts-to-your-sveltekit-project/ -->

<!-- <svelte:head>
	<link href="https://fonts.googleapis.com/css?family=Prompt" rel="stylesheet" />
</svelte:head> -->

<!-- src:
	local(''),
	url('/fonts/lora-v20-latin-500.eot?#iefix') format('embedded-opentype'),
	/* IE6-IE8 */ url('/fonts/lora-v20-latin-500.woff2') format('woff2'),
	/* Super Modern Browsers */ url('/fonts/lora-v20-latin-500.woff') format('woff'),
	/* Modern Browsers */ url('/fonts/lora-v20-latin-500.ttf') format('truetype'),
	Safari, Android, iOS url('/fonts/lora-v20-latin-500.svg#Lora') format('svg'); /* Legacy iOS */ -->
<style>
	a:link {
		text-decoration: none;
	}
	a:visited {
		text-decoration: none;
	}
	a:hover {
		text-decoration: none;
	}
	a:active {
		text-decoration: none;
	}
	/* @font-face {
		font-family: 'avenir';
		font-style: normal;
		font-weight: 500;
		src: local(''), url('/fonts/avenir.otf');
	} */
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
		margin: 50px;
		text-align: center;
		font-weight: bold;
		font-family: 'Roboto', sans-serif;
		color: #943a70;
		width: 50vw;
		/* padding-bottom: 100px; */
	}
	.plaatje {
		width: 50vw;
	}
	.link {
	}
	.link {
		display: block;
		background-color: #fadd4e;
		border: 10px solid #c63026;
		border-radius: 40px;
		padding: 20px;
		text-align: center;
		margin-top: 50px;
		margin-bottom: 50px;
		max-width: 311px;
		margin: 0 auto;
		/* white-space: nowrap; */
		/* overflow: hidden; */
		/* text-overflow: ellipsis; */
	}
	.kleinelettertjes {
		font-size: 0.7em;
		color: #fadd4e;
	}
	@media only screen and (max-width: 700px) {
		.container {
			flex-direction: column;
			height: 150vh;
		}
		.plaatje {
			width: 100vw;
			/* padding-top: 500; */
		}
		#textid {
			width: 95vw;
		}
		#imgid {
			/* position: relative; */
			/* height: 100%; */
		}
	}
	:global(body) {
		margin: 0;
		padding: 0;
	}
	/* body,
	html {
		margin: 0;
		padding: 0;
	}
	* {
		box-sizing: border-box;
	} */
</style>
