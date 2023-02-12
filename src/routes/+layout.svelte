<script>
	import '../app.css';
	import '@fontsource/roboto';
	import Navbar from '../components/Navbar.svelte';
	import Hero from '../components/Hero.svelte';
	import Content from '../components/Content.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<div class="w-full min-h-screen">
	<Navbar />
	<Hero />
	<Content />
	<Footer />
	<slot />
</div>
