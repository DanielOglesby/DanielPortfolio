<script>
  import Headshot from "../components/LandingPage/Headshot.svelte";
  import GithubButton from "../components/LandingPage/GithubButton.svelte";
  import LinkedInButton from "../components/LandingPage/LinkedInButton.svelte";
  import InstagramButton from "../components/LandingPage/InstagramButton.svelte";
  import TopNavbar from "../components/LandingPage/TopNavbar.svelte";
  import ButtonGroup from "../components/LandingPage/ButtonGroup.svelte";
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
