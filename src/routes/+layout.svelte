<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<div class="p-4 grid place-items-center h-screen bg-[url('/textures/noise.png')] bg-purple-50">
	{@render children()}
</div>
