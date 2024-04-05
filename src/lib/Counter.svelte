<script lang="ts">
  let count: number = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment} class="border rounded py-2 px-5">
  count is {count}
</button>
