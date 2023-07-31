<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>



<script>
	import Gallery from "../components/Gallery/Gallery.svelte";
	import InfoCard from "../components/InfoCard/InfoCard.svelte";

</script>




<section>
   <div class="flex items-center justify-center px-10 py-6 bg-white sm:px-6 lg:px-8 w-full">
    <InfoCard />
    </div>
    <Gallery />

</section>
