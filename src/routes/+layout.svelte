<script>
	import '../app.css'
	import Header from './header.svelte'
	import Footer from './footer.svelte'
</script>

<Header />
<main class="px-6 py-3 h-full"><slot /></main>
<Footer />
