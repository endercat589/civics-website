<script lang="ts">
    export let src = '';
</script>

<div class="hero" style="background-image: url({src});">
    <slot></slot>
</div>

<style lang="scss">
    @import '../app.scss';

    .hero {
        width: 100%;
        height: 25rem;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        background-size: cover;
        background-repeat: no-repeat;
        border-radius: 3rem;
        color: $clr-bg;
        font-size: 2rem;
        font-weight: bold;
    }
</style>