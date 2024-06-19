<script lang="ts">
	export let title: string;
	export let answers: number;
	export let user: string;
	export let date: string;
</script>

<a href="">
	<h3>{title}</h3>
</a>
<p>
	Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque, voluptates, magnam illum maiores
	mollitia quam expedita sint iusto ducimus ad voluptatem obcaecati quasi unde necessitatibus
	dolores molestiae neque quibusdam repellat?
</p>
<h5>feito por {user} em {date}</h5>
{#if answers !== 1}
	<h5>{answers} Respostas</h5>
{:else}
	<h5>{answers} Resposta</h5>
{/if}

<style>
	h5 {
		background-color: none;
	}
	h5:hover {
		background-color: magenta;
	}
</style>
