<script>
  import "./main.css";

  import logo from "./assets/svelte.png";
  import Counter from "./lib/Counter.svelte";
</script>

<main class="text-center p-4 mx-0">
  <img
    width="100"
    height="100"
    src={logo}
    alt="Svelte Logo"
    class="inline-block"
  />
  <h1 class="main-heading">Hello Vite!</h1>

  <Counter />

  <p class="max-w-xs sm:max-w-none my-4 mx-auto leading-5">
    Visit <a class="text-blue-600 underline" href="https://svelte.dev"
      >svelte.dev</a
    > to learn how to build Svelte apps.
  </p>

  <p class="max-w-xs sm:max-w-none my-4 mx-auto leading-5">
    Check out <a href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
    the officially supported framework, also powered by Vite!
  </p>
</main>
