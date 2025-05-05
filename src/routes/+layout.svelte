<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<div class="p-4 flex sm:items-center justify-center min-h-screen bg-[url('/textures/noise.png')] bg-purple-50">
	{@render children()}
</div>
