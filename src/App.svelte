<script>
  import SimpleHeadline from "./components/SimpleHeadline.svelte";
  import StyledHeadline from "./components/StyledHeadline.svelte";
  import DynamicStyledHeadline from "./components/DynamicStyledHeadline.svelte";
  import IfElse from "./components/IfElse.svelte";
  import Loops from "./components/Loops.svelte";
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <SimpleHeadline />
  <StyledHeadline />
  <DynamicStyledHeadline />
  <IfElse />
  <Loops />
  <p>
    Visit the
    <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
    to learn how to build Svelte apps.
  </p>
</main>
