<script>
    import "../global.scss";
    import "../site.scss";
    import Header from '$lib/sections/header/Header.svelte';
    import Nav from '$lib/sections/nav/Nav.svelte';

</script>

<main class="container">
	<header>
		<div class="title">
			<Header/>
		</div>
		<Nav/>
	</header>
	<div class="container" >
        <slot />
    </div>

	<footer />
</main>

<style>

</style>



