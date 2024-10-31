<script lang="ts">
	import Clock from './Clock.svelte';
	import DiscordInfo from './DiscordInfo.svelte';
	import SocialLink from './SocialLink.svelte';
	import SpotifyInfo from './SpotifyInfo.svelte';

	import GitHub from '$lib/components/icons/GitHub.svelte';
	import Envelope from '$lib/components/icons/Envelope.svelte';
	import Spotify from '$lib/components/icons/Spotify.svelte';
	import Meta from '$lib/components/Meta.svelte';
</script>

<Meta title="vornexx" description="My portfolio and personal website." />

<main class="wrapper fade">
	<h1 class="header">vornexx</h1>

	<p class="mt-4 text-gray-400">
		I'm <b>vornexx</b>, a person from
		<b>Trinidad & Tobago (Trinidad)</b>.
	</p>

	<div class="mt-4 flex gap-6">
		<SocialLink href="https://github.com/vornexx" name="GitHub">
			<GitHub />
		</SocialLink>

	
		<SocialLink
			href="https://spotify.vornexx.is-a.dev"
			name="Spotify"
		>
			<Spotify />
		</SocialLink>

		<SocialLink href="mailto:vornexx@fsb.com" name="Email">
			<Envelope />
		</SocialLink>
	</div>

	<Clock />

	<DiscordInfo />
	<SpotifyInfo />
</main>
