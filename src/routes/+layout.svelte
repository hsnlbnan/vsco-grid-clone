<script>
	import Footer from '../components/Footer/Footer.svelte';
	import Header from '../components/Header/Header.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header />
	<main>
		<slot />
	</main>
	<Footer />
</div>
