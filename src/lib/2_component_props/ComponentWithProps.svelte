<script>
    //Step 1 -> define a prop as a variable and suppla an optional default value
    export let name = 'Arthur';
    export let surname = 'Klezovich';
</script>

<div>
<!-- Step 2 -> use prop values in the UI layer -->
    <p>Name: {name}</p>
    <p>Surname: {surname}</p>
</div>