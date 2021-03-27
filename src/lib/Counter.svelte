<script lang="ts">
  let count: number = 0;

  const increment = () => {
    count += 1;
  };
</script>

<button class="bg-red-400 px-2 py-1 text-white rounded" on:click={increment}>
  Clicks: <span class="testclass">{count}</span>
</button>

<style>
  .testclass {
    @apply font-light text-green-500;
  }
</style>
