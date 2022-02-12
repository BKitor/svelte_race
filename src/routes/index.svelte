<script context="module">
	export const prerender = true;
</script>

<!-- <svelte:head>
	<title>Home</title>
</svelte:head> -->

<section>
	<!-- <div class="welcome">
		</div> -->
	<h1 class="text-3xl font-bold underline">Benjamin Kitor</h1>

	<picture>
		<source srcset="svelte-welcome.webp" type="image/webp" />
		<img src="svelte-welcome.png" alt="Welcome" />
	</picture>

	<h2 class="text-sky-400">Suck it Dom</h2>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
