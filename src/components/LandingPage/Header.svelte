<script>
  import Headshot from "./Headshot.svelte";
  import ButtonGroup from "./ButtonGroup.svelte";
  import TopNavbar from "./TopNavbar.svelte";
</script>

<section class=" flex">
  <div class="h-24 flex w-full">
    <div class="flex ml-4">
      <Headshot />
    </div>
    <div class="flex ml-8 order-1">
      <TopNavbar />
    </div>
    <div class="flex order-2 ml-auto">
      <ButtonGroup />
    </div>
  </div>
</section>
