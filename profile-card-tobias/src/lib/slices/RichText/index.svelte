<script>
	import { PrismicRichText } from '@prismicio/svelte';
	import Label from './Label.svelte';

	/** @type {import("@prismicio/client").Content.RichTextSlice} */
	export let slice;
</script>

<main>
	<section class="profile-card">
		<p>Tobias</p>
		<a href="https://github.com/TobiasVr23"><img src="c:\Users\Gebruiker\Pictures\Fdnd\download.png"></a>
	</section>
</main>

<style>
	main {
		display: flex;
		justify-content: center;
		align-items: center;
		margin: 0;
	}
	.profile-card {
		background: rgb(85,139,245);
		background: linear-gradient(180deg, rgba(85,139,245,1) 35%, rgba(204,221,255,1) 100%);
		width: 25em;
		min-height: 100vh;
		border-radius: 15px;
	}
</style>
