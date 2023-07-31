<script>
	import Card from '../Card/Card.svelte';
    import cards from '../../mock/data.json';

</script>

<main class="gallery">
	{#each cards as card}
	<Card {card} />
	{/each}
</main>

