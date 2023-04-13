<script>
	export let status;
	export let message1;
	export let message2;
</script>

<div class="min-h-full pt-16 pb-[100%] flex flex-col bg-white dark:bg-theme-100">
	<main
		class="flex-grow flex flex-col justify-center max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8"
	>
		<div class="flex-shrink-0 flex justify-center">
			<div class="inline-flex">
				<svg
					aria-hidden="true"
					focusable="false"
					data-prefix="fas"
					data-icon="cat"
					class="w-32 h-32 text-black dark:text-theme-200"
					role="img"
					xmlns="http://www.w3.org/2000/svg"
					viewBox="0 0 512 512"
				>
					<path
						fill="currentColor"
						d="M290.59 192c-20.18 0-106.82 1.98-162.59 85.95V192c0-52.94-43.06-96-96-96-17.67 0-32 14.33-32 32s14.33 32 32 32c17.64 0 32 14.36 32 32v256c0 35.3 28.7 64 64 64h176c8.84 0 16-7.16 16-16v-16c0-17.67-14.33-32-32-32h-32l128-96v144c0 8.84 7.16 16 16 16h32c8.84 0 16-7.16 16-16V289.86c-10.29 2.67-20.89 4.54-32 4.54-61.81 0-113.52-44.05-125.41-102.4zM448 96h-64l-64-64v134.4c0 53.02 42.98 96 96 96s96-42.98 96-96V32l-64 64zm-72 80c-8.84 0-16-7.16-16-16s7.16-16 16-16 16 7.16 16 16-7.16 16-16 16zm80 0c-8.84 0-16-7.16-16-16s7.16-16 16-16 16 7.16 16 16-7.16 16-16 16z"
					/>
				</svg>
			</div>
		</div>
		<div class="py-16">
			<div class="text-center">
				<p class="text-4xl mb-4 font-semibold text-brand-100 dark:text-theme-200 uppercase tracking-wide">
					{status}
				</p>
				<h1
					class="mt-2 text-4xl font-extrabold text-neutral-900 dark:text-white tracking-tight sm:text-5xl"
				>
					{message1}
				</h1>
				<p class="mt-2 text-base text-neutral-500 dark:text-gray-300">{message2}</p>
				<div class="mt-6">
					<a
						href="../"
						class="text-base font-medium text-brand-100 dark:text-theme-200 hover:text-brand-200 dark:hover:text-theme-200"
					>
						Go Home&nbsp;<span aria-hidden="true">&rarr;</span>
					</a>
				</div>
			</div>
		</div>
	</main>
</div>
