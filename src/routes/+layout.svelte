<script>
	import Navbar from '$lib/components/Navbar.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<Navbar />

<div class="container pt-5 mt-3">
	<slot />
</div>

<Footer />
