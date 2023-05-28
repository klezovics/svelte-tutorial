<script>
    import BlueBox from "./BlueBox.svelte";
    import RedBox from "./RedBox.svelte";
</script>

<div>
    <p>I am a container for multiple boxes</p>

<!--    We have a component which has other custom components inside of it-->
    <RedBox/>
    <BlueBox/>
</div>