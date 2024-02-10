<svelte:head>
	<title>Главная</title>
</svelte:head>

<nav <nav class="horizontal-menu plain">>
	<ul>
		{#each nav as link}
			{#if link.isShow}
			<li class ={link.lox} ><a href={link.href} class="link">{link.title}</a></li>
			{/if}
		{/each}
	</ul>
</nav>

<div class="contayner">
	<div class="hone_rot"></div>
	<div class="rot"></div>
	<div class="cot">
		<p class="h1">ВПК "Братишка"</p>
		<p class="p1">город Ахтубинск, Астраханская область</p>
	</div>
</div>

<div class="container">
	<slot></slot>
</div>
<style>
	.container {
		max-width: 1400px;
		margin: 50px auto;
	}
</style>