<header>
	<nav class="pages">
		<a href="/" class="link">Home</a>
		<a href="/projects" class="link">Projects</a>
		<a href="/cv" class="link">CV</a>
	</nav>

	<div class="links">
		<a href="https://github.com/TimB44"><img src="" alt="Github" /></a>
		<a href="TODO"><img src="" alt="Linkedin" /></a>
		<a href=""><img src="" alt="" /></a>
		<a href=""><img src="" alt="" /></a>
		<a href=""><img src="" alt="" /></a>
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
		border-width: 0px;
		border-bottom-width: 2px;
		border-style: 	dashed;
		border-color: var(--color-bd);
		/* border: 3px var(--color-bd); */
	}
	.pages {
		display: flex;
		justify-content: space-around;
		align-items: center;
	}
	.link {
		font-size: 1.5rem;
		padding: 5px 10px;
	}


	nav {
		display: flex;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
	}

	a:hover {
		color: var(--color-theme-1);
		background-color: var(--color-bd)	;
		/* text-decoration: dotted; */
	}
</style>
