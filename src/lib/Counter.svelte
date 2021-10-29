<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button
  on:click={increment}
  class="rounded-full bg-red-100 hover:bg-red-200 active:bg-red-300 text-red-600 py-4 px-8 border-2 border-transparent outline-none w-48 tabular-nums focus:border-opacity-100"
>
  Clicks: {count}
</button>
