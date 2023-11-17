<!-- <script>
	import { card } from 'card.svelte';
</script> -->


<section class="flex">
	<!-- Card 1 -->
	<div class="container flex-start justify-center items-center p-10">
		<div class="space-y-10 text-center flex flex-col items-center">
			<div class="card">
				<header class="card-header text-2xl">This is the first card</header>
				<section class="p-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde, maxime.</section>
				<img src="images/pexels-dids-2911521.jpg" alt="abstract pink, black and yellow painting">
				<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Click for more info!</button>
				</div>
			</div>
		</div>
	
		<!-- Card 2 -->
	<div class="container mx-auto flex-start justify-center items-center p-10">
		<div class="space-y-10 text-center flex flex-col items-center">
			<div class="card">
				<header class="card-header text-2xl">This is the second card</header>
				<section class="p-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde, maxime.</section>
				<img src="images/pexels-jadson-thomas-542556.jpg" alt="abstract pink, black and yellow painting">
				<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Click for more info!</button>
				</div>
			</div>
		</div>
	
		<!-- Card 3 -->
	<div class="container mx-auto flex-start justify-center items-center p-10">
		<div class="space-y-10 text-center flex flex-col items-center">
			<div class="card">
				<header class="card-header text-2xl">This is the third card</header>
				<section class="p-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde, maxime.</section>
				<img src="images/pexels-steve-johnson-1266808.jpg" alt="abstract pink, black and yellow painting">
				<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Click for more info!</button>
				</div>
			</div>
		</div>
</section>

<!-- <style lang="postcss">
	figure {
		@apply flex relative flex-col;
	}
	figure svg,
	.img-bg {
		@apply w-64 h-64 md:w-80 md:h-80;
	}
	.img-bg {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
			glow 5s linear infinite;
	}
	@keyframes glow {
		0% {
			@apply bg-primary-400/50;
		}
		33% {
			@apply bg-secondary-400/50;
		}
		66% {
			@apply bg-tertiary-400/50;
		}
		100% {
			@apply bg-primary-400/50;
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(1.5);
		}
	}
</style> -->
