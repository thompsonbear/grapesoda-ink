<script lang="ts">
	import VenueIcon from '$lib/icons/venue.svelte';
	import InstagramIcon from '$lib/icons/instagram.svelte';
	import FacebookIcon from '$lib/icons/facebook.svelte';
	import CashappIcon from '$lib/icons/cashapp.svelte';
</script>

<div class="flex flex-col items-center gap-12 text-purple-900">
	<div class="mt-8 flex flex-col items-center justify-center space-y-4 text-center">
		<img
			src="/images/profile.webp"
			alt="A self portrait of Grape Soda - tattoo artist"
			class="w-54 rounded-full ring-2 ring-purple-800 ring-offset-2"
		/>
		<div class="flex flex-col items-center gap-2">
			<h1 class="font-title text-3xl">Jenna Bear</h1>
			<p class="font-medium text-purple-900/70">Apprentice Tattoo Artist in Knoxville, TN</p>
			<a
				class="flex items-center gap-1 text-sm text-purple-900/70 hover:underline"
				href="https://www.facebook.com/ghostboytattoo"
				target="_blank"
			>
				<svg xmlns="http://www.w3.org/2000/svg" class="w-4" viewBox="0 0 24 24"
					><g fill="none" fill-rule="evenodd"
						><path
							d="m12.593 23.258l-.011.002l-.071.035l-.02.004l-.014-.004l-.071-.035q-.016-.005-.024.005l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427q-.004-.016-.017-.018m.265-.113l-.013.002l-.185.093l-.01.01l-.003.011l.018.43l.005.012l.008.007l.201.093q.019.005.029-.008l.004-.014l-.034-.614q-.005-.018-.02-.022m-.715.002a.02.02 0 0 0-.027.006l-.006.014l-.034.614q.001.018.017.024l.015-.002l.201-.093l.01-.008l.004-.011l.017-.43l-.003-.012l-.01-.01z"
						/><path
							fill="currentColor"
							d="M12 2a9 9 0 0 1 9 9c0 3.074-1.676 5.59-3.442 7.395a20.4 20.4 0 0 1-2.876 2.416l-.426.29l-.2.133l-.377.24l-.336.205l-.416.242a1.87 1.87 0 0 1-1.854 0l-.416-.242l-.52-.32l-.192-.125l-.41-.273a20.6 20.6 0 0 1-3.093-2.566C4.676 16.589 3 14.074 3 11a9 9 0 0 1 9-9m0 2a7 7 0 0 0-7 7c0 2.322 1.272 4.36 2.871 5.996a18 18 0 0 0 2.222 1.91l.458.326q.222.155.427.288l.39.25l.343.209l.289.169l.455-.269l.367-.23q.293-.186.627-.417l.458-.326a18 18 0 0 0 2.222-1.91C17.728 15.361 19 13.322 19 11a7 7 0 0 0-7-7m0 3a4 4 0 1 1 0 8a4 4 0 0 1 0-8m0 2a2 2 0 1 0 0 4a2 2 0 0 0 0-4"
						/></g
					></svg
				>
				<span>Ghost Boy Tattoo</span>
			</a>
		</div>
	</div>

	<div class="grid aspect-square w-full max-w-96 grid-cols-2 grid-rows-2 rounded-4xl">
		<a
			href="https://venue.ink/grapesoda.ink"
			target="_blank"
			class="flex flex-col items-center justify-center gap-2 rounded-tl-4xl border border-t-2 border-l-2 bg-[url('/textures/noise.png')] font-medium tracking-wide transition-colors hover:bg-purple-800/10"
		>
			<VenueIcon />
			<span class="text-center">Book a Tattoo</span>
		</a>
		<a
			href="https://www.instagram.com/grapesoda.ink/"
			target="_blank"
			class="flex flex-col items-center justify-center gap-2 rounded-tr-4xl border border-t-2 border-r-2 bg-[url('/textures/noise.png')] font-medium tracking-wide transition-colors hover:bg-purple-800/10"
		>
			<InstagramIcon />
			<span class="text-center">Instagram</span>
		</a>
		<a
			href="https://www.facebook.com/grapesoda.ink"
			target="_blank"
			class="flex flex-col items-center justify-center gap-2 rounded-bl-4xl border border-b-2 border-l-2 bg-[url('/textures/noise.png')] font-medium tracking-wide transition-colors hover:bg-purple-800/10"
		>
			<FacebookIcon />
			<span class="text-center">Facebook</span>
		</a>
		<a
			href="https://cash.app/$grapesodaink"
			target="_blank"
			class="flex flex-col items-center justify-center gap-2 rounded-br-4xl border border-r-2 border-b-2 bg-[url('/textures/noise.png')] font-medium tracking-wide transition-colors hover:bg-purple-800/10"
		>
			<CashappIcon />
			<span class="text-center">Tip Me</span>
		</a>
	</div>
</div>
