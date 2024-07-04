<script lang="ts">
  //import router from "page";
  import Comic from './routes/comic/+page.svelte';
  import Home from "./routes/home.svelte";
  
  let page = Home;

  //<router('/', () => page = Home);
  //router('/Comic', () => page = Comic);
 

  //router.start(); 

</script>

<svelte:component this={page} />