<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<main><button on:click={increment}>Clicked {count} times</button></main>
