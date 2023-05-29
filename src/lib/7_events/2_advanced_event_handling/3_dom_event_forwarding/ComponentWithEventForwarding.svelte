<script>
    import CustomButton from './CustomButton.svelte';

    function handleClick() {
        alert('clicked');
    }
</script>

<!--// The click handler is passed on as a prop from parent-->
<CustomButton on:click={handleClick}/>