<script>
    let count = 0;
    let countSquared = count * count

    function handleClick() {
        count += 1;
    }
</script>

<button on:click={handleClick}>
    Clicked {count} {count === 1 ? 'time' : 'times'}
</button>

<!-- Why doesn't this update ? -->
<p>Count squared is {countSquared}</p>