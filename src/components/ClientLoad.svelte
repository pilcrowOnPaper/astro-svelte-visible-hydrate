<script lang="ts">
    import { onMount } from "svelte";

    let message = "not yet...";

    onMount(() => {
        console.log("client:load")
        message = "yes!";
    });
</script>

<link rel="stylesheet" href="./styles.css" />
<h2>client:load</h2>
<p>Hydrated?: {message}</p>
