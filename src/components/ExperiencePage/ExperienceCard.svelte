<script>
  export let title = "Invitation Homes";
  export let description =
    "Created full stack customer facing web app for finding homes for lease";
  export let badges = [
    "Svelte/SvelteKit",
    "TypeScript",
    "neutral",
    "neutral",
    "neutral",
  ];
</script>

<div
  class="card w-96 bg-gradient-to-r from-cyan-500 to-blue-500 text-black mt-4"
>
  <div class="card-body">
    <h2 class="card-title">{title}</h2>
    <p>{description}</p>
    <div>
      <div class="badge badge-neutral text-white">{badges[0]}</div>
      <div class="badge badge-neutral text-white">{badges[1]}</div>
      <div class="badge badge-neutral text-white">{badges[2]}</div>
      <div class="badge badge-neutral text-white">{badges[3]}</div>
      <div class="badge badge-neutral text-white">{badges[4]}</div>
    </div>
  </div>
</div>
