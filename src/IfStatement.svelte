<script>
  export let testVal;
</script>

<main>
  {#if testVal === 1}
    The value is 1
  {:else}
    The value is not 1
  {/if}
</main>
