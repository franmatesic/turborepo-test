<script lang="ts">
    import {Button, counter} from '@repo/shared';

    function decrement() {
        counter.update((value: number) => value - 1);
    }
</script>

<Button color="green" on:click={decrement}>
    {$counter}
</Button>
