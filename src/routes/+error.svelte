<script>
    import { onMount } from 'svelte';

    onMount(() => {
        if (window.location.pathname !== '/') {
            window.location.href = '/';
        }
    });
</script>