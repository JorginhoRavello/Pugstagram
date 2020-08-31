<script>
    import Card from './Card.svelte';
    import Loader from './Loader.svelte';
    
    export let posts = [];
</script>

<style>
    .TimeLine {
        padding: 4em 0 0 0;
    }
</style>

<div class="TimeLine">
    <div class="TimeLine-containe">
       {#each posts as post }
        <Card {...post} />
           {:else}
           <loader />

       {/each}
    </div>
</div>
