<script>
  import OutsideRoutes from "$lib/OutsideRoutes.svelte";

  onMount(() => {
    console.log("mounted");
  });
</script>

<main>
  <OutsideRoutes />
  <h1>Welcome to SvelteKit</h1>

  <p>
    <FormButton>button</FormButton>
  </p>

  <Test />

  <SharedFragment />
</main>

<style>
  main {
    padding: 50px;
  }
</style>
