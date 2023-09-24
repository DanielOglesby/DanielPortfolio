<script>
  import BottomNav2 from "../components/BottomNav2.svelte";
  import Headshot from "../components/Headshot.svelte";
  import Browser from "../components/Browser.svelte";
  import GithubButton from "../components/GithubButton.svelte";
  import LinkedInButton from "../components/LinkedInButton.svelte";
  import InstagramButton from "../components/InstagramButton.svelte";
  import TopNavbar from "../components/TopNavbar.svelte";
  import ButtonGroup from "../components/ButtonGroup.svelte";
</script>

<main>
  <section class="px-[15vw] py-10 flex">
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
  <div class="flex p-10 justify-center">
    <p class="text-center">
      Hello! My name is <a
        class="text-sky-400"
        href="https://www.linkedin.com/in/daniel-oglesby-b68086b3/"
        target="_blank">Daniel Oglesby</a
      >. A software engineer from Dallas, TX. I'm passionate about building
      beautiful, scalable applications.
    </p>
  </div>
</main>

<style>
</style>
