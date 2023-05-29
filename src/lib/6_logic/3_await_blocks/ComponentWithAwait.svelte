<script>
    let promise = getRandomNumber();

    async function getRandomNumber() {
        //Put in bad URL here to demonstrate an error state
        const res = await fetch(`https://www.random.org/integers/?num=1&min=1&max=6&col=1&base=10&format=plain&rnd=new`);
        const text = await res.text();

        if (res.ok) {
            return text;
        } else {
            throw new Error(text);
        }
    }

    function handleClick() {
        promise = getRandomNumber();
    }
</script>

<button on:click={handleClick}>
    generate random number
</button>

{#await promise}
    <p>...waiting</p>
{:then number}
    <p>The number is {number}</p>
{:catch error}
    <p style="color: red">{error.message}</p>
{/await}
