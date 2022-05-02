<script lang="ts">
  import logo from "./assets/svelte.png";
  import Counter from "./lib/Counter.svelte";
</script>

<main class="w-2/4 mx-auto text-center">
  <img class="w-60 mx-auto" src={logo} alt="Svelte Logo" />
  <h1 class="text-orange-500 uppercase text-6xl font-thin my-8">
    Hello Typescript!
  </h1>

  <Counter />

  <p class="py-4">
    Visit <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte
    apps.
  </p>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
    the officially supported framework, also powered by Vite!
  </p>
</main>

<style>
  a {
    @apply underline;
  }
</style>
