<script lang="ts">
    import {
        HandCoins
    } from "lucide-svelte";
    import { Button } from "$lib/components/ui/button";
    // import { pump } from "$lib/ao/relay";
    import type { Meme } from "$lib/models/Meme";
    import { DEFAULT_QUANTITY } from "$lib/constants";

    export let meme: Meme;

    // async function _dump() {
    //     await pump(DEFAULT_QUANTITY, "0", meme.Pool, meme.TokenA);
    // }
</script>

<Button size="sm" class="bg-blue-500 text-white" >
    <HandCoins class="w-4 h-4 mr-2" />
    Dump
</Button>
