<script>
    let m = { x: 0, y: 0 };

    function handleMousemove(event) {
        m.x = event.clientX;
        m.y = event.clientY;
    }
</script>

<div class="box" on:mousemove={handleMousemove}>
    The mouse position is {m.x} x {m.y}
</div>

<style>
    div { width: 100%; height: 100%; }
    .box { background-color: #eee; padding: 1em; }
</style>