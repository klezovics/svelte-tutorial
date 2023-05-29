<script>
    function handleClick() {
        alert('no more alerts')
    }
</script>

<!--The alert will run only once-->
<button on:click|once={handleClick}>
    Click me
</button>