<script>
    import Box from './Box.svelte';
    import BoxWithDefaultContents from "./BoxWithDefaultContents.svelte";
</script>

<Box>
    <h2>Hello!</h2>
    <p>This is content from parent component.</p>
</Box>

<Box/>

<BoxWithDefaultContents>
    <h2>Hello!</h2>
    <p>This is content from parent component.</p>
</BoxWithDefaultContents>


<BoxWithDefaultContents/>



