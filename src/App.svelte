<script>
  import Tailwind from "./components/Tailwind.svelte";
  import Spliter from "./Components/Spliter.svelte";

  export let name;
</script>

<Tailwind />

<main>
  <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
  <Spliter />
</main>

<style>
</style>
