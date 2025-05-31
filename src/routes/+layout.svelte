<script lang="ts">
	import '../app.css';
	import Footer from '$lib/layout/footer.svelte';
	import Header from '$lib/layout/header.svelte';

	import type { NavLink } from '$lib/types';

	const links: NavLink[] = [
		{ text: 'About', href: '/about' },
		{ text: 'Portfolio', href: '/portfolio' },
		{ text: 'Flash', href: '/flash' },
		{ text: 'Book A Tattoo', href: '/book' }
	];

	let { children } = $props();
</script>

<div class="flex min-h-screen flex-col items-center bg-gradient-to-b from-violet-800 to-violet-300">
	<Header {links} />
	<div class="w-full max-w-[1280px] p-4">
		{@render children()}
	</div>
</div>
<Footer {links} />
