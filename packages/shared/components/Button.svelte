<script lang="ts">
    export let color: string = "red";
</script>

<button style="background-color: {color}" on:click>
    <slot/>
</button>

<style>
    button {
        padding: 0.2rem 1rem;
        border-radius: 1rem;
    }
</style>