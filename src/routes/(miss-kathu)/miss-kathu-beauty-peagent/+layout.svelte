<script>
	import '$lib/app.css';
	import { Crown } from 'svelte-iconoir';
</script>

<nav
	aria-label="Site Nav"
	class="mx-auto flex max-w-screen-xl items-center justify-between p-4 z-50"
>
	<a href="/" class="inline-flex items-center justify-center gap-1 text-lg rounded-lg">
		<span class="sr-only">Logo</span>
		<Crown class="h-8 w-8 -rotate-12 text-pink-600" />
		Miss Kathu <span class="hidden md:inline-block">Beauty Peagent</span>
	</a>

	<ul class="flex items-center gap-2 text-sm font-medium text-gray-500">
		<!-- <li class="hidden lg:block">
			<a class="rounded-lg px-3 py-2" href="/"> Who are we </a>
		</li>

		<li><a class="rounded-lg px-3 py-2" href="/"> Mission </a></li> -->

		<li>
			<a class="inline-flex bg-pink-600 text-white items-center gap-2 rounded px-3 py-2" href="/">
				&larr; Girl Child <span class="hidden md:inline-block">Education</span>
			</a>
		</li>
	</ul>
</nav>
<slot />
