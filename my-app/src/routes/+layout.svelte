<script>
	let { children } = $props();
</script>

<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
	<a href="/settings">Settings</a>
    <a href="/add">Add</a>
    <a href="/login">Login</a>
	<a href="/blog">blog</a>
</nav>

{@render children()}