<script>
    import NewPageSvg from "./NewPageSvg.svelte";
</script>


<nav class="flex flex-row justify-center gap-8 bg-teal-100 text-cyan-800 py-5 sticky top-0 z-50 shadow-md">
    <a href="/">Home</a>
    <a href="/chat">Chat</a>
    <a href="/search">Search</a>
    <a href="https://github.com/solunian/medtalk" target="_blank" class="flex flex-row">
        GitHub <NewPageSvg/>
    </a>
</nav>