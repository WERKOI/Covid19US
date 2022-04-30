<script>
	export let segment;
</script>

<style>
	@media (min-width: 769px) {
	  nav {
		border-bottom: solid gray 1px;
	  }
	}
  </style>


<nav class="navbar" role="navigation" aria-label="main navigation">
	<div class="navbar-brand">
	  <a rel="prefetch" href="/" class="navbar-item">
		<img src="logo.jpg" width="32" alt="virus" />
	  </a>
	  <span
		class="navbar-burger"
		aria-label="menu"
		aria-expanded="false">
		<span aria-hidden="true" />
		<span aria-hidden="true" />
		<span aria-hidden="true" />
	  </span>
	</div>
	<div class="navbar-menu">
	  <div class="navbar-start">
		<a
		  rel="prefetch"
		  href="/"
		  class="navbar-item">
		  Home
		</a>
		<a
		  rel="prefetch"
		  href="/about"
		  class="navbar-item">
		  About
		</a>
	  </div>
	</div>
  
  </nav>