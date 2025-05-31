<script lang="ts">
	const { links } = $props();

	let currentYear = new Date().getFullYear();
</script>

<footer class="w-screen bg-violet-300 pt-12">
	<div class="relative h-22">
		<span
			class="animate-wave3 absolute bottom-0 left-0 block h-22 w-full bg-[url('/svg/sodawave3.svg')] bg-repeat-x"
		></span>
		<span
			class="animate-wave2 absolute bottom-0 left-0 block h-16 w-full bg-[url('/svg/sodawave2.svg')] bg-repeat-x"
		></span>
		<span
			class="animate-wave1 absolute bottom-0 left-0 block h-6 w-full bg-[url('/svg/sodawave1.svg')] bg-repeat-x"
		></span>
	</div>
	<div class="flex justify-center bg-gradient-to-b from-violet-600 to-violet-800 backdrop-blur-lg">
		<nav class="grid w-full max-w-[1280px] gap-8 p-8 lg:grid-cols-2">
			<div>
				<p class="font-display text-6xl text-violet-100">Grape Soda Ink</p>
				<p class="text-xl font-medium tracking-wide text-violet-100">
					© Copyright {currentYear}
				</p>
			</div>

			<div class="flex flex-col gap-2">
				<a
					href="/"
					class="font-title transform-all font-semibold text-violet-100 decoration-2 underline-offset-2 duration-100 hover:text-white hover:underline hover:underline-offset-4 focus:text-white focus:underline-offset-4"
					>Home</a
				>
				{#each links as { text, href }}
					<a
						{href}
						class="font-title transform-all font-semibold text-violet-100 decoration-2 underline-offset-2 duration-100 hover:text-white hover:underline hover:underline-offset-4 focus:text-white focus:underline-offset-4"
						>{text}</a
					>
				{/each}
			</div>
		</nav>
	</div>
</footer>
