<script>
	export let segment;
</script>

<!-- svelte-ignore a11y-no-redundant-roles -->
<nav class="navbar" role="navigation" aria-label="main navigation">
	<div class="navbar-brand">
		<a href="/" class="navbar-item">
		<img src="logo.png" alt="virus">
		</a>
		<span
		class="navbar-burger"
		arial-label="menu"
		aria-expanded="false">
		<span aria-hidden="true"></span>
		<span aria-hidden="true"></span>
		<span aria-hidden="true"></span>
		</span>
	</div>
	<div class="navbar-menu">
		<div class="navbar-start">
			<a href="/" class="navbar-item">Home</a>
			<a href="/about" class="navbar-item">About</a>
		</div>
	</div>
</nav>