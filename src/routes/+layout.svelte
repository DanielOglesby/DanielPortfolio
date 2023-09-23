<script lang="ts">
  import "../app.css";
  import "@fontsource/archivo";
</script>

<slot />

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.blue.400);
    font-family: "Archivo";
  }
</style>
