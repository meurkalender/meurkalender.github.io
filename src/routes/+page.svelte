<script lang="ts">
	import { base } from '$app/paths';
</script>

<!-- <div class="imgdiv">
    <img class="plaatje" src="{base}/images/horizontaal.png" alt="" />
</div> -->
<div class="textdiv">
	<h1>WELKOM!</h1>
	<p>Goed nieuws! De tweede editie van de Meurkalender is uit *!</p>
	<p>Bestel jouw Meurkalender via deze link:</p>
	<div class="linkdiv">
		<a class="link" href="www.google.com">ik wil een meurkalender bestellen</a>
	</div>
	<p>Wees snel want de oplage is beperkt! en vergeet niet: Vrijdag Veegdag!</p>
	<p class="kleinelettertjes">
		*Wetenschappelijk onderzoek wijst uit dat de 2e editie 2.34 x hoger scoort kwa humor.
	</p>
</div>

<style>
    .textdiv {
        text-align: center;
        /* display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center; */
        width: 400px;
    }
	.imgdiv {
		display: flex;
		height: 90vh;
		justify-content: center; /* Add this line */
	}
	.plaatje {
		height: 90vh;
		margin: auto; /* Add this line */
	}
	.link {
		background-color: #fadd4e;
		border: 10px solid #c63026;
		border-radius: 40px;
		padding: 20px; 
	}
	.linkdiv {
		margin: 50px;
	}
    .kleinelettertjes {
        font-size: 0.7em;
    }
</style>
