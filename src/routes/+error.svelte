<script context="module">
	import { page } from '$app/stores';
</script>

<script>
	import Error from '$lib/error.svelte';
</script>

{#if $page.status !== undefined && $page.error?.message !== undefined}
	<Error
		status={$page.status}
		message1={$page.error.message}
		message2={"Sorry, we couldn't proccess that request."}
	/>
{:else}
	<Error
		status={500}
		message1="Unknown Error"
		message2={"Sorry, we couldn't proccess that request."}
	/>
{/if}
