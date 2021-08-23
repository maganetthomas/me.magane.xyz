<script lang="ts">
	import "./components/Header.svelte"
</script>

<Header site_name="me.magane.xyz"/>

<style>
	:global(*, *::before, *::after) {
		padding: 0;
		margin: 0;
		box-sizing: inherit;
	}

	:global(html, body) {
		height: 100%;
		width: 100%;
	}

	:global(body) {
		display: grid;
		place-items: center;
		box-sizing: border-box;
	}
</style>
