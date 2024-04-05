<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main class="p-4 grid place-items-center text-center">
  <div class="grid place-items-center gap-5">
    <div class="flex gap-2">
      <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
        <img src={viteLogo} alt="Vite Logo" />
      </a>
      <a href="https://svelte.dev" target="_blank" rel="noreferrer">
        <img src={svelteLogo} alt="Svelte Logo" />
      </a>
    </div>
    <h1 class="font-bold">Vite + Svelte</h1>

    <Counter />

    <p>
      Check out <a class="text-blue-600 cursor-pointer" href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
    </p>

    <p>
      Click on the Vite and Svelte logos to learn more
    </p>
  </div>

</main>
