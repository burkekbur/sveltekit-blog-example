<!-- lib/components/Header.svelte -->
<script>
    import { base } from '$app/paths';
</script>

<header>
    <a href="{base}/">Home</a>

    <nav>
        <ul>
            <li>
                <a href="{base}/lorem-ipsum">Lorem</a>
            </li>
            <li>
                <a href="{base}/blog">Blog</a>
            </li>
            <li>
                <a href="{base}/markdown">Markdown</a>
            </li>
        </ul>
    </nav>
</header>

<style lang="scss">
    header {
        padding: 1rem;
        background: #bada55;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }

    ul {
        margin: 0;
        list-style-type: none;
        display: flex;
        gap: 1rem;
    }

    a {
        text-decoration: none;
        color: inherit;
    }
</style>
