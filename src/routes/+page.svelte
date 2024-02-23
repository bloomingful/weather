<script>
    import Greet from '../lib/Greet.svelte'
</script>
  
<h1 class="text-4xl font-bold underline">
    Hello world!
</h1>

<style lang="postcss">
    :global(html) {
      background-color: theme(colors.blue.300);
    }
</style>

<Greet />