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
				<a href="http://localhost:5173/" class="text-xl uppercase"><strong>Skeleton</strong></a>
			</svelte:fragment>
			<svelte:fragment slot="trail">
				<!-- Change these links and text -->
				<a
					class="btn btn-sm variant-ghost-surface"
					href="/gallery.page.svelte"
					target="_blank"
					rel="noreferrer"
				>
					Gallery
				</a>
				<a
					class="btn btn-sm variant-ghost-surface"
					href="https://twitter.com/SkeletonUI"
					target="_blank"
					rel="noreferrer"
				>
					Twitter
				</a>
				<a
					class="btn btn-sm variant-ghost-surface"
					href="https://github.com/skeletonlabs/skeleton"
					target="_blank"
					rel="noreferrer"
				>
					GitHub
				</a>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>

	<!-- Change the class of the sidebar to be hidden on small screens -->
	<svelte:fragment slot="sidebarLeft">Sidebar Left</svelte:fragment>
	<!-- Page Route Content -->
	<slot />
</AppShell>
