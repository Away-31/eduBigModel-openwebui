<!-- src/routes/new-page.svelte -->
<script>

  import { onMount } from 'svelte';
  import ClassControl from '$lib/components/workspace/control/EduControl/ClassControl.svelte';

  onMount(() => {
    console.log('New page has been mounted!');
  });
</script>

<main>
  <ClassControl />
</main>

<style>
  main {
    text-align: center;
    padding: 20px;
  }
</style>