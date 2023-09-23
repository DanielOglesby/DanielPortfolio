<script lang="ts">
  import "../app.css";
</script>

<slot />

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.blue.400);
  }
</style>
