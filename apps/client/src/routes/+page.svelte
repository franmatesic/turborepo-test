<script lang="ts">
    import {Button, counter} from '@repo/core';
</script>

<Button on:click={() => counter.update(value => value + 1)}>
    {$counter}
</Button>
