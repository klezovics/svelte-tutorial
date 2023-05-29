<div class="box">
<!--    All children of component are injected here.-->
<!--    Similar to react's children prop-->
    <slot></slot>
</div>

<style>
    .box {
        width: 300px;
        border: 1px solid #aaa;
        border-radius: 2px;
        box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
        padding: 1em;
        margin: 0 0 1em 0;
        background-color: orange;
    }
</style>