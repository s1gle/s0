<script>
	let { children } = $props();
</script>

<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
	<a href="/settings">Settings</a>
	<a href="/blog">blog</a>
	<a href="/a/deeply/nested/route">a deeply nested route</a>
</nav>

{@render children()}