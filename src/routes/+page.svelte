<script lang="ts">
	import { theme } from '$lib/stores';

	function handleSwitch(colorScheme: string) {
		$theme = colorScheme;
	}
</script>

<h1>BROCK STUDIO</h1>

<button on:click={() => handleSwitch('dark')}>Dark</button>
<button on:click={() => handleSwitch('light')}>Light</button>
