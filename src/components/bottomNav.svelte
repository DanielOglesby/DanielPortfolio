<script lang="ts">
  import githubLogo from "../lib/assets/github-logo.svg";
  import linkedinLogo from "../lib/assets/linkedin-logo.svg";
  import instagram from "../lib/assets/instagram.svg";

  let color = "white";
  let githubHover = false;
  let linkedinHover = false;
</script>

<div class="btm-nav">
  <button class="hover:active ease-out duration-100">
    <a href="https://github.com/DanielOglesby">
      <img src={githubLogo} alt="GitHub" class="h-7 w-7 invert" />
    </a>
  </button>
  <button class="hover:active ease-out duration-100">
    <a href="https://www.linkedin.com/in/daniel-oglesby-b68086b3/">
      <img src={linkedinLogo} alt="LinkedIn" class="h-7 w-7 invert" />
    </a>
  </button>
  <button class="hover:active ease-out duration-100">
    <a href="https://www.instagram.com/beltsquatguy/">
      <img src={instagram} alt="Instagram" class="h-7 w-7 invert" />
    </a>
  </button>
</div>
