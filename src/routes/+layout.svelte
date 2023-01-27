<script>
	import '../app.css'
	import logo from "$lib/assets/logo.png"
</script>

<nav>
	<ul>
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
	ul {
		display: flex;
		flex-direction: row;
		justify-content: space-evenly;
		align-items: center;
	}

</style>

