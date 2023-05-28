<script>
    // Step 1 -> Define component state
    let counterValue = 0;


    // Step 2 -> Define component methods
    function increment() {
        counterValue += 1;
    }
    function decrement() {
        counterValue -= 1;
    }
</script>

<div>
<!--    Step 3 -> Link component state and methods to the UI-->
    <h1>Counter {counterValue}</h1>
    <button on:click={increment}>+</button>
    <button on:click={decrement}>-</button>
</div>