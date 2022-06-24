<script>
  import Title from "$lib/Title.svelte";
  import "../styles/global.css";
</script>

<header>
  <Title title="Nija Gaming Guides" />
</header>

<main>
  <!-- page content -->
  <slot><!-- optional fallback --></slot>

  <footer>
    <p>Copyright 2022 Ninja Gaming Guides</p>
  </footer>
</main>

<style>
  header {
    display: flex;
    justify-content: center;
  }
  main {
    max-width: 960px;
    margin: 20px auto;
  }
  footer {
    text-align: center;
  }
</style>
