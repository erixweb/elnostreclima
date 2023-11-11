<script lang="ts">
	import "../../app.css"
</script>
<svelte:head>
	<title>
		Article
	</title>
	<link rel="preload" href="/fonts/Switzer-Medium.woff2" as="font" type="font/woff2" crossorigin="anonymous">
	<link rel="preload" href="/fonts/Switzer-Black.woff2" as="font" type="font/woff2" crossorigin="anonymous">
</svelte:head>
<main class="max-w-[45em] px-[20px] m-auto">
	<slot />
</main>
