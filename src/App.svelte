<script lang="ts">
	import Tailwindcss from './Tailwind.svelte';
  export let name: string;
</script>

<style>



</style>

<Tailwindcss />

<main class="mx-auto bg-blue-200 text-center">
	<h1 class="font-black">Hello {name}!</h1>
  <p>
    Visit the
    <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
    to learn how to build Svelte apps.
  </p>
</main>
