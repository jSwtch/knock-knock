<script>
  import { jokes } from "../jokes.js";
</script>

<style>

</style>

<svelte:head>
  <title>Knock Knock</title>
</svelte:head>

{#each jokes as joke}
  <div>{joke.prompt1}</div>
  <div>{joke.response1}</div>
    <div>{joke.prompt2}</div>
  <div>{joke.response2}</div>
  <div>{joke.joke}</div>
{/each}
