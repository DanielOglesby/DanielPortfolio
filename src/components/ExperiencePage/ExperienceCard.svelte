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
  export let link = "https://www.invitationhomes.com/";
</script>

<div
  class="card w-[500px] bg-gradient-to-r from-cyan-500 to-blue-500 text-black mt-4 cursor-pointer"
>
  <a href={link}>
    <div class="card-body">
      <h2 class="card-title">{title}</h2>
      <p>{description}</p>
      <div>
        <div class="badge badge-black text-white">{badges[0]}</div>
        <div class="badge badge-black text-white">{badges[1]}</div>
        <div class="badge badge-black text-white">{badges[2]}</div>
        <div class="badge badge-black text-white">{badges[3]}</div>
        <div class="badge badge-black text-white">{badges[4]}</div>
      </div>
    </div>
  </a>
</div>
