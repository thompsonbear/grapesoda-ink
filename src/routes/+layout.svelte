<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Grape Soda Ink</title>
	<meta name="description" content="Tattoo Artist in Knoxville, TN at Ghost Boy Tattoo" />
</svelte:head>

<div
	class="flex min-h-screen justify-center bg-purple-50 bg-[url('/textures/noise.png')] p-4 sm:items-center"
>
	{@render children()}
</div>
