<script>
  import ExperienceCard from "../../components/ExperiencePage/ExperienceCard.svelte";
  import TopNavbar from "../../components/LandingPage/TopNavbar.svelte";
  import Headshot from "../../components/LandingPage/Headshot.svelte";
  import ButtonGroup from "../../components/LandingPage/ButtonGroup.svelte";
  import Header from "../../components/LandingPage/Header.svelte";
</script>

<main class="px-[15vw] py-10">
  <Header />
  <section class="p-10 flex flex-col">
    <div class="flex justify-center">
      <div class="mt-8">
        <ExperienceCard
          title="Invitation Homes"
          description="Created full stack customer facing web app for finding homes for lease"
          badges={[
            "Svelte/SvelteKit",
            "TypeScript",
            "PostgreSQL",
            "Terraform",
            "Heroku",
          ]}
          link="https://www.invitationhomes.com/"
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
          link="https://cs.utdallas.edu/"
        />
      </div>
    </div>
  </section>
</main>
