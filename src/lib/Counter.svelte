<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<div>
<button on:click={increment}>
  count is {count}
</button>
</div>
