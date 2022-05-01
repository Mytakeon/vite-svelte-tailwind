<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button
  class="text-red-500 bg-red-50 cursor-pointer w-52 rounded-3xl px-5 py-3 focus:border-2 focus:border-orange-500 active:bg-orange-100"
  on:click={increment}
>
  Clicks: {count}
</button>
