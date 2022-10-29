<script lang="ts">
    import { onMount } from "svelte";

    let message = "not yet...";

    onMount(() => {
        console.log("client:visible")
        message = "yes!";
    });
</script>

<link rel="stylesheet" href="./styles.css" />
<h2>client:visible</h2>
<p>Hydrated?: {message}</p>
