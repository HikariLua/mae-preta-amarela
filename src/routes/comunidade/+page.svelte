<script>
	import Post from './Post.svelte';
</script>

<div>
	<h1>Bem Vindo(a)!</h1>
	<a href="">Entrar</a>
	<a href="">Registrar-se</a>
</div>
<p>
	Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores, temporibus dignissimos minus
	alias ex rerum ipsam tempora omnis vel impedit officia nobis sunt minima sed ea, quod explicabo,
	corporis natus!
</p>
<hr />

<section>
	<div class="posts">
		<Post
			title="Essa é uma dúvida genérica para testes."
			answers={34}
			user="Usuario"
			date="02/07/2023 23:58:32"
		/>
	</div>
	<div class="indexer">
		<input type="text" placeholder="Pesquisar" />
		<button>
			<img src="/mag-glass.svg" alt="Pesquisar" />
		</button>
	</div>
</section>

<style>
button img {
	max-width: 2vh;
}
</style>
