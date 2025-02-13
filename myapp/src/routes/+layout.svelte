<script>
	let { children } = $props();
</script>

<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
	<a href="/settings">Settings</a>
	<a href="/new">new</a>
	<a href="/b">b</a>
	<a href="/a">a deeply nested route</a>
</nav>

{@render children()}

