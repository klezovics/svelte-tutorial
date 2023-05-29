<script>
    import Inner from './Inner.svelte';

    // Components can send events to each other
    function handleMessage(event) {
        alert(event.detail.text);
    }
</script>

<Inner on:message={handleMessage}/>