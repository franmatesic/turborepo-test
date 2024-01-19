<script lang="ts">
    import {Button, counter} from '@repo/core';
</script>

<Button color="green" on:click={() => counter.update(value => value - 1)}>
    {$counter}
</Button>
