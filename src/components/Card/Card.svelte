<script lang="ts">
    import { createEventDispatcher } from 'svelte';
    import type { CardType } from '../../types/card-type'; 

    export let card: CardType; 
    
</script>

<figure class="block break-inside-avoid cursor-pointer relative m-0">
    <img src={card.url} alt={card.alt_description} class="w-full h-auto select-none align-middle" />
</figure>
