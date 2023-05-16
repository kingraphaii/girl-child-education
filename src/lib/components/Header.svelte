<script>
	import { Sparks, OpenInWindow } from 'svelte-iconoir';
</script>

<section
	class="text-gray-600 bg-gradient-to-r from-pink-700 via-pink-400 to-pink-700 body-font bg-gray-100"
>
	<div class="container max-w-screen-xl px-4 py-1 mx-auto">
		<div class="flex gap-2 items-center font-semibold justify-center text-white">
			<Sparks stroke-width={2} /> Never dim your light! <Sparks
				class="rotate-90"
				stroke-width={2}
			/>
		</div>
	</div>
</section>
<nav class="bg-white border-pink-800 shadow-2xl py-7">
	<div
		class="container h-full relative max-w-screen-xl px-4 py-2 flex items-center justify-between mx-auto"
	>
		<div
			class="relative after:text-xs after:font-bold after:-right-4 after:content-['by\a0Tshepiso\a0Tsogang'] after:text-pink-700 after:absolute after:-bottom-3"
		>
			<a href="/" class="text-4xl font-thin tracking-tight"
				><span class="font-black text-pink-600">Girl Child</span> Education</a
			>
		</div>
		<div class="md:flex hidden items-center justify-center text-lg font-extralight">
			<a
				href="#our-mission"
				class="px-4 py-2 leading-5 text-lg hover:bg-pink-400 hover:text-white focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out"
				>Our Mission</a
			>
			<a
				href="#highlights"
				class="px-4 py-2 leading-5 hover:bg-pink-400 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out hover:text-white"
				>Highlights</a
			>
			<a
				href="#contribute"
				class="px-4 py-2 leading-5 hover:bg-pink-400 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out hover:text-white"
				>Get Involved</a
			>
			<a
				href="/miss-kathu-beauty-peagent"
				class="px-5 flex rounded items-center gap-2 py-3 ml-2 leading-5 bg-pink-600 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out text-white"
			>
				<span class="font-bold">Miss Kathu</span> Peagent
				<OpenInWindow />
			</a>
		</div>
	</div>
</nav>
