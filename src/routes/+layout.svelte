<nav>
	<a href="/">Inicio</a>
	<a href="/sobre">Sobre</a>
	<a href="/comunidade">Comunidade</a> |
	<button>Alto Contraste</button>
</nav>

<main>
	<slot />
</main>

<footer>
	<div>
		<a href=""> <img src="/insta.svg" alt="" /> Instagram </a>
		<a href=""> <img src="/whatsapp.svg" alt="" /> Whatsapp </a>
		<a href=""> <img src="/linkedin.svg" alt="" /> Linkedin </a>
		<a href=""> <img src="/github.svg" alt="" /> Github </a>
	</div>
	<h2>&copy;2024</h2>
</footer>

<style>
	a {
		background-color: magenta;
	}
	footer a img {
		max-width: 5vw; /* base size relative to viewport width */
		width: 100%; /* ensure it scales within its container */
		height: auto; /* maintain aspect ratio */
	}

	/* Media queries for different screen sizes */
	@media (max-width: 1200px) {
		footer a img {
			max-width: 3vw;
		}
	}

	@media (max-width: 900px) {
		footer a img {
			max-width: 4vw;
		}
	}

	@media (max-width: 600px) {
		footer a img {
			max-width: 6vw;
		}
	}

	@media (max-width: 400px) {
		footer a img {
			max-width: 8vw;
		}
	}
</style>
