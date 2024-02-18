<script>
	import '../app.pcss';
	import '@fontsource-variable/manrope';
</script>

<svelte:head>
	<!-- Primary Meta Tags -->
	<title>Build in Public Deals</title>
	<meta name="title" content="Build in Public Deals" />
	<meta
		name="description"
		content="Discounts and credits for creators and developers who are building in public"
	/>

	<!-- Open Graph / Facebook -->
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://buildinpublic.deals/" />
	<meta property="og:title" content="Build in Public Deals" />
	<meta
		property="og:description"
		content="Discounts and credits for creators and developers who are building in public"
	/>
	<meta property="og:image" content="https://buildinpublic.deals/images/meta-tags.png" />

	<!-- Twitter -->
	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:url" content="https://buildinpublic.deals/" />
	<meta property="twitter:title" content="Build in Public Deals" />
	<meta
		property="twitter:description"
		content="Discounts and credits for creators and developers who are building in public"
	/>
	<meta property="twitter:image" content="https://buildinpublic.deals/images/meta-tags.png" />

	<!-- Meta Tags Generated with https://metatags.io -->
</svelte:head>

<div class="min-w-screen dark min-h-screen bg-slate-950 text-slate-50">
	<slot />
</div>
