<!-- Child.svelte -->
<script>
    import { getContext } from 'svelte';

    // Get the sharedData store from the context
    // For this to work, this component must be a child of a component which creates a store
    const sharedData = getContext('sharedData');

    // Update the shared data with a new value
    function updateSharedData() {
        sharedData.set('Updated shared data from Child component');
    }
</script>

<section>
    <h2>Child Component</h2>
    <p>Shared Data: {$sharedData}</p>
    <button on:click={updateSharedData}>Update Shared Data</button>
</section>
