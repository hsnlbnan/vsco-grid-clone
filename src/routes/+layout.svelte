<script>
	import '../app.scss';
	import Header from '../components/Header/Header.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>
</div>
