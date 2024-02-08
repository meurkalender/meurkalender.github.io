<!-- <script lang="ts">
	import '/styles/fonts.css';
</script> -->
<svelte:head>
	<link
		rel="icon"
		href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%221em%22 font-size=%2280%22>💩</text></svg>"
	/>
	<title>Meurkalender</title>
</svelte:head>

<slot />

<style>
	:global(body) {
		background: linear-gradient(#943a70, #509f61, #b6c9e9, #dddaed, #b6c9e9, #509f61, #943a70);
		background-repeat: no-repeat;
		background-attachment: fixed;
		height: 100%;
		margin: 0;
		padding: 2rem;
	}
</style>
