<script>
// @ts-nocheck

    import Header from '$lib/components/Header.svelte';
    import '$lib/styles/style.scss'
</script>

<Header />

<main>
  <slot />
</main>

<footer>Hello, I'm the footer.</footer>

