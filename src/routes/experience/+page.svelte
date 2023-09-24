<script>
  import ExperienceCard from "../../components/ExperiencePage/ExperienceCard.svelte";
  import TopNavbar from "../../components/LandingPage/TopNavbar.svelte";
</script>

<section class="p-10 flex flex-col">
  <div class="m-8">
    <TopNavbar />
  </div>
  <div class="flex justify-center">
    <div>
      <ExperienceCard
        title="Invitation Homes"
        description="Created full stack customer facing web app for finding homes for lease"
        badges={[
          "Svelte/SvelteKit",
          "TypeScript",
          "neutral",
          "neutral",
          "neutral",
        ]}
      />
      <ExperienceCard
        title="The University of Texas at Dallas"
        description="Studied Computer Science and graduated with a 3.2 GPA"
        badges={[
          "Data Structures/Algorithms",
          "Machine Learning",
          "Computer Architecture",
          "Automata Theory",
          "Network Security",
        ]}
      />
      <ExperienceCard />
      <ExperienceCard />
    </div>
  </div>
</section>
