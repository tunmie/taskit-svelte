<script>
	import logo from '$lib/assets/logo.png';
</script>


<header>
	<div class='logo'>
		<a href='/'>
			<img src={logo} alt='our logo' />
			<h1>List Things</h1>
		</a>
	</div>


	<nav>
		<ul>
			<li><a href='/'>Why Us?</a></li>
		</ul>
		<ul>
			<li><a href='/'>Contact</a></li>
		</ul>
		<ul>
			<li><a href='/'>Features</a></li>
		</ul>
	</nav>
	<div class="auth-container">
		<button >Sign Up</button>
		<button class="login-btn">Log In</button>
	</div>

</header>


<style>
	header {
		display: flex;
		justify-content: space-between;
		background-color: #F0FFF0;
	}

	ul {
		position: relative;
		list-style: none;
		margin: 0;
		padding: 3em;
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	ul li {
		height: 100%;
	}

	ul li a {
		font-size: 18px;
		font-weight: 600;
		line-height: 100%;
		letter-spacing: -0.02em;
		color: #020130;
		font-family: "Poppins", sans-serif;
	}

	a {
		text-decoration: none;
	}

	.logo {
		/* width: 3em; */
		/* height: 3em; */
		margin-left: 88px;
		margin-top: 20px;
		margin-bottom: 20px;
	}

	.logo a {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		width: 100%;
	}

	.logo a h1 {
		font-family: "Poppins", sans-serif;
		font-size: 20px;
		font-weight: 700;
		letter-spacing: -0.02em;
		color: #020130;
	}

	nav {
		display: flex;
		justify-content: center;
	}

	.auth-container {
		display: flex;
		justify-content: center;
		align-items: center;
    margin-right: 40px;
	}


	button {
		background-color: #020130;
		color: #fff;
		padding: 10px 25px;
    margin: 18px;
		border-radius: 12px;
		border: none;
		font-size: 18px;
    letter-spacing: -0.02em;
	}

  .login-btn {
    background: none;
    color: #020130;
    font-family: "Poppins", sans-serif;
    font-weight: 600;
  }


</style>