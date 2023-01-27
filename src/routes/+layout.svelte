<script>
	import '../app.css'
	import logo from "$lib/assets/logo.png"
</script>

<nav class='container mx-auto'>
	<ul class='flex flex-row justify-around'>
		<li>
			<div class="logo">
				<img src={logo} alt="our logo" class="px-">
				<a href="/">List Things</a>
			</div>
		</li>
		<li>
			<a class="nav-item">Why Us?</a>
		</li>
		<li>
			<a>Contact</a>
		</li>
		<li>
			<a>Features</a>
		</li>
	</ul>
</nav>

<slot/>

<style>
	nav {
		background-color: #F0FFF0;
	}

</style>

