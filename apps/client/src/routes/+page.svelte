<script lang="ts">
    import {Button, counter} from '@repo/shared';

    function increment() {
        counter.update((value: number) => value + 1);
    }
</script>

<Button on:click={increment}>
    {$counter}
</Button>
