<script>
  let title = "Hello page";
  function updateTitle() {
    title = "I can change my title in Hello page";
  }
</script>

<h2>{title}</h2>
<input type="text" bind:value={title} />
