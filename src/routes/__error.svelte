<script context="module">
  export function load({ error }) {
    return {
      props: { message: error.message },
    };
  }
</script>

<script>
  export let message;
</script>

<div class="error">
  <h2>Ooops</h2>
  <p>{message}</p>
  <a href="/guides">View all guides...</a>
</div>

<style>
  .error {
    text-align: center;
    margin-buttom: 60px;
  }
</style>
