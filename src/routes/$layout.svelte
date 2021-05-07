<style>
    main {
        flex: 1;
        display: flex;
        flex-direction: column;
        padding: 1rem;
        width: 100%;
        max-width: 600px;
        margin: 0 auto;
        box-sizing: border-box;
        text-align: center;
    }

    footer {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        padding: 40px;
    }

    footer a {
        font-weight: bold;
    }

    @media (min-width: 480px) {
        footer {
            padding: 40px 0;
        }
    }
</style>

<script lang="ts">
    import "../app.css";
</script>

<main>
    <slot />
</main>

<footer>
    <p>Built with <a href="https://kit.svelte.dev" target='_blank'>sveltekit</a>. Deployed in <a href="https://kit.svelte.dev" target='_blank'>netlify</a></p>
</footer>
