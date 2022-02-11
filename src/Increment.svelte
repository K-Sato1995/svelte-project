<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
  // Gets triggered whenever the count value gets updated.
  $: console.log("the count is " + count);
</script>

<main><button on:click={increment}>Clicked {count} times</button></main>
