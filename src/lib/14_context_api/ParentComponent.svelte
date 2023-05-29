<!-- App.svelte -->
<script>
    import { setContext } from 'svelte';
    import { writable } from 'svelte/store';
    import ChildComponent from "./ChildComponent.svelte";

    // Create a writable store to hold the shared data
    const sharedData = writable('Initial shared data');
    // Set the sharedData store as the context value
    setContext('sharedData', sharedData);
</script>

<main>
    <h1>App Component</h1>
    <ChildComponent />
</main>
