<script>
	import { Instagram } from 'svelte-iconoir';
	let videos = ['/walk.mp4', '/selfie.mp4'];
	let vidObj;
	let videoSrc = 0;
	let showWalk = false;
	function toggleModal() {
		showWalk = !showWalk;
	}
</script>

<div
	class="relative flex flex-col items-center justify-center min-h-screen bg-white bg-cover min-w-screen"
>
	<div
		class="flex flex-col items-center justify-center p-10 mx-auto lg:flex-row lg:max-w-6xl lg:p-0"
	>
		<div
			class="container relative z-20 flex flex-col w-full px-5 pb-1 pr-12 mb-16 text-2xl text-gray-700 lg:w-1/2 sm:px-0 md:px-10 sm:items-center lg:items-start lg:mb-0"
		>
			<h1
				class="relative z-20 text-5xl font-extrabold leading-none text-pink-600 xl:text-6xl sm:text-center lg:text-left"
			>
				Shine through<br class="md:hidden lg:block" />
				<span class="text-gray-800">your flaws.</span>
			</h1>
			<p
				class="relative z-20 block mt-6 text-base text-gray-500 xl:text-xl sm:text-center lg:text-left"
			>
				Miss Kathu is a local beauty pageant in the Northern Cape Province, providing young girls
				aged 18-29 with essential skills for national and international pageants through workshops
				on public speaking, grooming, and socio-economic projects.
			</p>
		</div>
		<div class="relative w-full px-5 rounded-lg cursor-pointer md:w-2/3 lg:w-1/2 group xl:px-0">
			<div class="absolute top-0 left-0 w-11/12 -mt-20 opacity-50">
				<svg
					class="w-full h-full ml-4 text-pink-100"
					viewBox="0 0 200 200"
					xmlns="http://www.w3.org/2000/svg"
				>
					<path
						fill="currentColor"
						d="M45,-78C58.3,-70.3,69,-58.2,75.2,-44.4C81.3,-30.7,82.9,-15.3,83.5,0.4C84.2,16,83.8,32.1,76.5,43.9C69.2,55.7,55.1,63.3,41.2,69.4C27.3,75.4,13.6,80,-0.7,81.2C-15.1,82.5,-30.1,80.3,-41.2,72.6C-52.2,64.9,-59.2,51.6,-67.1,38.5C-75.1,25.5,-83.9,12.8,-83.8,0C-83.8,-12.7,-74.9,-25.4,-65.8,-36.4C-56.7,-47.4,-47.4,-56.7,-36.4,-65.7C-25.4,-74.7,-12.7,-83.5,1.6,-86.2C15.9,-89,31.8,-85.7,45,-78Z"
						transform="translate(100 100)"
					/>
				</svg>
			</div>
			<div class="relative overflow-hidden rounded-md shadow-2xl cursor-pointer group">
				<div class="absolute flex items-center justify-center w-full h-full">
					<!-- svelte-ignore a11y-click-events-have-key-events -->
					<span
						on:click={toggleModal}
						class="flex items-center justify-center p-2 px-3 bg-pink-900/30 rounded-lg text-slate-200 shadow-2xl"
					>
						<Instagram />
						Coach Tshepi
					</span>
				</div>
				<!-- svelte-ignore a11y-missing-attribute -->
				<video
					bind:this={vidObj}
					on:ended={(e) => {
						if (videoSrc == 0) {
							videoSrc = 1;
						}
						vidObj.src = videos[videoSrc];
					}}
					class="z-10 object-cover align-top w-full h-[44rem]"
					autoplay
				>
					<track kind="captions" />
					<source src="/walk.mp4" type="video/mp4" />
					Your browser does not support the video tag.
				</video>
				<!-- <img
					src="https://static.wixstatic.com/media/1f3484_0344d7e46087405899699fecedad9f12~mv2.jpg/v1/fill/w_563,h_750,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/1f3484_0344d7e46087405899699fecedad9f12~mv2.jpg"
					class="z-10 object-cover align-top w-full h-72"
				/> -->
			</div>
		</div>
	</div>
</div>

<!-- our mission-->
<div
	class="relative flex flex-col items-center justify-center bg-gray-50 py-12 bg-cover min-w-screen"
>
	<div
		class="flex flex-col flex-col-reverse items-center justify-center p-10 mx-auto lg:flex-row lg:max-w-6xl lg:p-0"
	>
		<div
			class="container relative z-20 flex flex-col w-full px-5 pr-12 mb-16 text-2xl text-gray-700 lg:w-1/2 sm:px-0 md:px-10 sm:items-center lg:items-start lg:mb-0"
		>
			<h1
				class="relative z-20 font-sans text-4xl font-extrabold leading-none text-black sm:text-5xl xl:text-6xl sm:text-center lg:text-left"
			>
				<span class="relative">
					<span
						class="absolute bottom-0 left-0 inline-block w-full h-4 mb-1 -ml-1 transform -skew-x-3 bg-pink-200"
					/>
					<span class="relative">Our Mission,</span>
				</span>
				<span class="relative block text-pink-400">at Miss Kathu.</span>
			</h1>
			<p
				class="relative z-20 block mt-6 text-base text-gray-500 xl:text-lg sm:text-center lg:text-left"
			>
				To empower women and girls to become the best version of themselves. To be inclusive of the
				population in society that is usually marginalised due to how they choose to identify
				themselves, hence we train young girls regardless of weight, height, religion, race ect
			</p>

			<p class="mt-6 text-xs text-gray-500 rounded-full">Connect with Tshepiso on Socials?</p>
		</div>
		<div class="relative w-full pr-10 rounded-lg cursor-pointer md:w-2/3 lg:w-1/2 group">
			<div class="relative rounded-md">
				<script
					src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"
				></script>
				<lottie-player
					src="https://assets5.lottiefiles.com/packages/lf20_zwijnhaz.json"
					background="transparent"
					class="max-w-md min-w-sm"
					speed="1"
					loop
					autoplay
				/>
			</div>
		</div>
	</div>
</div>

<section class="relative rounded-lg my-5 min-w-screen animation-fade animation-delay">
	<div class="container px-1 mx-auto sm:px-10 md:px-0">
		<div class="flex flex-col items-center justify-center w-full md:flex-row">
			<div class="flex justify-center w-full md:max-w-md md:mr-8 lg:mr-12">
				<!-- svelte-ignore a11y-missing-attribute -->
				<img src="/mk-1.svg" class="z-10 object-cover w-full h-full" />
			</div>
			<div
				class="w-full max-w-md px-4 pb-10 text-xs text-center md:pb-0 sm:text-sm lg:text-base md:max-w-lg md:w-full md:text-left"
			>
				<h2
					class="text-2xl font-bold leading-snug sm:text-3xl md:text-4xl lg:text-5xl md:leading-tight md:mt-10"
				>
					Our Vision<br />
					at Miss Kathu.
				</h2>

				<p class="mt-4 sm:mt-6 md:max-w-sm">
					To create an inclusive society that leaves nobody behind that is aligned with the United
					Nations 2030 Agenda. The pageant creates very strong willed and empowered young leaders
					who can contribute something valuable to themselves and various societies at large. The
					pageant wants the contestants to be able to compete on a global scale and become global
					icons that will be ambassadors of change.
				</p>

				<button
					class="flex justify-center w-full max-w-xs py-4 mx-auto mt-10 text-sm font-semibold text-black transition-colors duration-100 bg-pink-500 rounded hover:bg-pink-600 hover:text-white focus:bg-pink-600 focus:text-white md:max-w-sm md:mx-0"
				>
					Connect With Us
				</button>

				<p class="text-gray-700 mt-10 text-md">
					&#10075;&#10075;We aim to instil self confidence within the youth to become positive role
					models within society who will develop into economic participants that break the negative
					cycle of socio-economic issues such as unemployment, poverty, hunger and gender based
					violence.&#10076;&#10076;
				</p>

				<div class="mt-4">
					<div class="self-center font-semibold text-gray-900">Tshepiso Tsogang, Founder</div>
				</div>
			</div>
		</div>
	</div>
</section>
