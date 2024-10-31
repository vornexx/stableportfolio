<script lang="ts">
	import Meta from '$lib/components/Meta.svelte';
	import Project from './Project.svelte';
</script>

<Meta title="Projects – vornexx" description="My projects." />

<main class="wrapper fade">
	<h1 class="header">Projects</h1>

	<p class="mt-4 mb-8 text-gray-400">Some of my projects.</p>

	<Project
		name="example"
		href="https://example.com"
		src="/images/projects/nimi.png"
	>
		example
	</Project>


</main>
