<script>
    // for tailwind css
    import "../app.css";

    import Footer from "../components/global/footer.svelte";
    import Nav from "../components/global/nav.svelte";
</script>

<Nav />
<slot></slot>
<Footer />
