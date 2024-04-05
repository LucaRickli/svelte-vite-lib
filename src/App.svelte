<script lang="ts">
  import svelteLogo from '$ass/svelte.svg'
  import Counter from '$lib/Counter.svelte'
  import viteLogo from '/vite.svg'
</script>

<main class="site-container">
  <div>
    <div>
      <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
        <img src={viteLogo} alt="Vite Logo" />
      </a>
      <a href="https://svelte.dev" target="_blank" rel="noreferrer">
        <img src={svelteLogo} alt="Svelte Logo" />
      </a>
    </div>
    <h1>Vite + Svelte</h1>

    <p>
      Check out 
      <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>,
      the official Svelte app framework powered by Vite!
    </p>

    <p class="font-extralight mb-3">
      Click on the Vite and Svelte logos to learn more
    </p>
    
    <Counter />
  </div>
</main>

<style lang="postcss" scoped>
  .site-container {
    @apply p-4 grid place-items-center text-center;

    & > div {
      @apply grid place-items-center gap-5 container;

      & div {
        @apply flex gap-2;
      }

      & img {
        @apply h-20 w-20;
      }

      & h1 {
        @apply font-bold text-5xl mb-3;
      }

      & a {
        @apply text-blue-600 cursor-pointer;
      }
    }
  }

</style>