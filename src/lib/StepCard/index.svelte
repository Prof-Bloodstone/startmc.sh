<script>
    export let title;
</script>

<section class="card">
    <div class="card-header">
        <h2 class="card-title">{ title }</h2>
    </div>
    <div class="card-content">
        <slot />
    </div>
</section>

<style>
    .card {
        padding: 1em;
        display: flex;
        flex-direction: column;
        width: 100%;
        background-color: var(--bg-light-alt);
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.3);
        position: relative;
        margin-bottom: 2em;
    }

    .card-header {
        margin-bottom: 1em;
    }

    .card-title {
        margin: 0;
        font-weight: normal;
    }
</style>