<script lang="ts">
	//import router from 'page';
	//const comic = (event: MouseEvent) => {
	//  router("/Comic")
	//}
</script>

<nav id="desktop-nav">
	<div class="logo">Personal portfolio website</div>
	<div>
		<ul class="nav-links">
			<li><a href="#about">About Me</a></li>
			<li><a href="#experience">Experience</a></li>
			<li><a href="#projects">Projects</a></li>
			<li><a href="#contact">Contact Me</a></li>
			<li>
				<div class="bth-container" style="position: relative; top: -5px;">
					<!--<button class="btn btn-color-2 project-btn" on:click={comic}> XKCD Comic</button>-->
				</div>
			</li>
		</ul>
	</div>
</nav>

<style>
	nav,
	.nav-links {
		display: flex;
	}

	nav {
		justify-content: space-around;
		align-items: center;
		height: 17vh;
	}

	.nav-links {
		gap: 2rem;
		list-style: none;
		font-size: 1.5rem;
	}

	a {
		color: black;
		text-decoration: none;
		text-decoration-color: white;
		transition: all 300ms ease;
	}

	a:hover {
		color: grey;
		text-decoration: underline;
		text-underline-offset: 0.5rem;
		text-decoration-color: rgb(181, 181, 181);
	}

	.logo {
		font-size: 2rem;
	}

	.logo:hover {
		cursor: default;
	}
</style>
