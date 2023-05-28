<script>

    import ComponentWithManyProps from "./ComponentWithManyProps.svelte";

    const pkg = {
        name: 'svelte',
        version: 3,
        speed: 'blazing',
        website: 'https://svelte.dev'
    };
</script>

<!--We can use this spread operator syntax to spread a bunch of properties-->
<ComponentWithManyProps {...pkg}/>