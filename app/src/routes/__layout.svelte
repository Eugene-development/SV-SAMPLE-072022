<script context="module">
	import '../app.css';
	import Header from '$layout/header/v_001/index.svelte';
	import Footer from '$layout/footer/v_001/index.svelte';
</script>

<Header />
<main>
	<slot />
</main>
<Footer />
