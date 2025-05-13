<script lang="ts">
	import '../app.css';
	import Footer from '$lib/layout/footer.svelte';
	import Header from '$lib/layout/header.svelte';

	let { children } = $props();
</script>

<div class="flex min-h-screen flex-col items-center bg-gradient-to-b from-violet-800 to-violet-300">
	<Header />
	<div class="w-full max-w-[1280px] p-4">
		{@render children()}
	</div>
</div>
<Footer />
