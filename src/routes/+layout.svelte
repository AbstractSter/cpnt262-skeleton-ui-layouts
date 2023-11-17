<script>
	import '../app.postcss';
	import { AppShell, AppBar } from '@skeletonlabs/skeleton';
</script>

<!-- App Shell -->
<AppShell>
	<svelte:fragment slot="header">
		<!-- App Bar -->
		<AppBar>
			<svelte:fragment slot="lead">
				<a href="http://localhost:5173/" class="text-4xl uppercase"><strong>SS</strong></a>
			</svelte:fragment>
			<svelte:fragment slot="trail">
				<!-- Change these links and text -->
				<a
					class="btn btn-md variant-ghost-surface"
					href="/gallery"
					target="_blank"
					rel="noreferrer"
				>
					Gallery
				</a>
				<a
					class="btn btn-md variant-ghost-surface"
					href="/blog"
					target="_blank"
					rel="noreferrer"
				>
					Blog
				</a>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>

	<!-- Change the class of the sidebar to be hidden on small screens -->
	<svelte:fragment slot="sidebarLeft">Sidebar Left</svelte:fragment>
	<!-- Page Route Content -->
	<slot />
</AppShell>
