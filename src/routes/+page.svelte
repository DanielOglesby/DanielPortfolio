<script>
  import BottomNav2 from "../components/BottomNav2.svelte";
  import Headshot from "../components/Headshot.svelte";
  import Browser from "../components/Browser.svelte";
  import GithubButton from "../components/GithubButton.svelte";
  import LinkedInButton from "../components/LinkedInButton.svelte";
  import InstagramButton from "../components/InstagramButton.svelte";
</script>

<main class="p-10">
  <div class="h-24 flex">
    <div class="flex ml-4">
      <Headshot />
    </div>
    <div class="flex ml-4">
      <GithubButton />
    </div>
    <div class="flex ml-4">
      <LinkedInButton />
    </div>
    <div class="flex ml-4">
      <InstagramButton />
    </div>
  </div>
</main>

<style>
</style>
