<script lang="ts">
  import githubLogo from "../lib/assets/github-logo.svg";
  import linkedinLogo from "../lib/assets/linkedin-logo.svg";
  import resume from "../lib/assets/resume.svg";

  let color = "white";
  let githubHover = false;
  let linkedinHover = false;
</script>

<div class="btm-nav">
  <button class="hover:active ease-out duration-100">
    <a href="https://github.com/DanielOglesby">
      <img src={githubLogo} alt="GitHub" class="h-7 w-7" />
    </a>
  </button>
  <button class="hover:active ease-out duration-100">
    <a href="https://www.linkedin.com/in/daniel-oglesby-b68086b3/">
      <img src={linkedinLogo} alt="LinkedIn" class="h-7 w-7 invert" />
    </a>
  </button>
  <button class="hover:active ease-out duration-100">
    <a>
      <img src={resume} alt="LinkedIn" class="h-7 w-7 invert" />
    </a>
  </button>
</div>
