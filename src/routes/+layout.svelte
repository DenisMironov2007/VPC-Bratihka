<svelte:head>
	<title>Главная</title>
</svelte:head>

<nav>
	{#each nav as link}
		{#if link.isShow}
			<a href={link.href} class="link">{link.title}</a>
		{/if}
	{/each}
	<div class="animation start-home"></div>
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

<script>
	const nav = [
		{ 
			title: 'Главная',
			href: '/',
			isShow: true
		},
		{ 
			title: 'Занятия',
			href: '/about',
			isShow: true
		},
		{
			title: 'Медиа',
			href: '/media',
			isShow: true
		},
		{
			title: 'Достижения',
			href: '/lessons',
			isShow: true
		},
		{
			title: 'Контакты',
			href: '/new',
			isShow: true
		}
	]
</script>
<style>
	.container {
		max-width: 1400px;
		margin: 50px auto;
	}
</style>