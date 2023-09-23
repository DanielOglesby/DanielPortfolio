<script>
  import BottomNav2 from "../components/BottomNav2.svelte";
  import Headshot from "../components/Headshot.svelte";
  import Browser from "../components/Browser.svelte";
</script>

<main>
  <section class="flex justify-center items-center h-screen flex-col">
    <div class="flex my-12">
      <Browser></Browser>
    </div>
    <div class="flex w-1/2">
      <p class="justify-center text-center">
        Recent Software Engineering graduate from The University of Texas at
        Dallas. With a passion for technology and problem-solving, I am excited
        to connect and learn!
      </p>
    </div>
    <div>
      <BottomNav2 />
    </div>
  </section>
</main>

<style>
</style>
