<div class="box">
    <slot>
<!--        Default contents are shown if nothing is given to the box-->
        <em>This is default contents</em>
        <em>Showing since content was provided</em>
    </slot>
</div>

<style>
    .box {
        width: 300px;
        border: 1px solid #aaa;
        border-radius: 2px;
        box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
        padding: 1em;
        margin: 0 0 1em 0;
        background-color: green;
    }
</style>