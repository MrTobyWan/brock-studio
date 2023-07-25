<script lang="ts">
	// The ordering of these imports is critical to your app working properly
	import '@skeletonlabs/skeleton/themes/theme-crimson.css';
	// If you have source.organizeImports set to true in VSCode, then it will auto change this ordering
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	// Most of your app wide CSS should be put in this file
	import '../app.postcss';

	import { LightSwitch } from '@skeletonlabs/skeleton';
</script>

<div class="static">
	<nav class="absolute top-2 left-2">
		<ul>
			<li>Home</li>
		</ul>
	</nav>
	<div class="absolute top-2 right-2">
		<LightSwitch />
	</div>
</div>

<slot />
