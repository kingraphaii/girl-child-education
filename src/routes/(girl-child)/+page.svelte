<script>
	import TypedJs from '@loscrackitos/svelte-typed-js';
</script>

<section
	class="bg-cover h-[82vh] bg-center py-8 px-1"
	style="background-image: url('/amevi-wisdom.jpg')"
>
	<div
		class="container h-full relative max-w-screen-xl bordser border-grsay-50 px-4 py-2 bgd-white shadows rounded-lg mx-auto"
	>
		<div
			class="mx-auto left-2 p-5 top-2 lg:p-6 bg-black/30 backdrop-blur-sm lg:backdrop-blur selection:bg-black absolute text-black w-4/5 lg:w-1/3 rounded-dxl"
		>
			<h3 class="text-2xl lg:text-5xl font-light lg:font-thin text-white relative mb-8 select-none">
				<TypedJs
					strings={[
						'<span class="font-black tracking-tight">Every girl child deserves</span> to participate in economic development.',
						'<span class="font-black tracking-tight">Every girl child deserves</span> equal learning opportunities.',
						'<span class="font-black tracking-tight">Every girl child deserves</span> to receive quality education.'
					]}
					loop={false}
					smartBackspace={true}
					typeSpeed="8"
					backSpeed="9"
				>
					<span class="typing bg-black/40 text-white leading-[1.2]" />
				</TypedJs>
			</h3>
			<p
				class="text-lg mt-2 lg:mt-5 lg:mb-4 p-3 rounded-xld backdrop-blur-3xl bg-black/40 text-white lg:font-medium relative"
			>
				With your support, we can provide education to girls who may not have had the opportunity
				otherwise – altering the trajectory of their lives, the lives of their children and the
				future of their communities.
			</p>
		</div>

		<div
			class="mx-auto hidden lg:block backdrop-blur-sm bg-black/40 lg:rounded-xld right-3 p-3 top-1/2 select-none absolute text-black w-4/5 lg:w-1/3"
		>
			<h3 id="h3" class="text-3xl lg:text-3xl font-bold text-white relative">
				<span class="typing bg-black/30 rounded-lgd px-2 text-white leading-[1.2]">Objective</span>
			</h3>
			<p
				class="text-lg mt-3 text-white bg-black/40 rounded-xld p-4 mb-3 lg:font-thin relative leading-tight"
			>
				For girl child to depend on education for economic freedom, to take and keep a girl in
				school with tools that will eliminate barriers that will hinder with their education.
			</p>
		</div>
	</div>
</section>

<div id="our-mission" class="h-72 bg-gradient-to-t from-[#f79cb089]">
	<div class="h-full flex justify-center items-center px-6 lg:px-0 lg:mx-16 mt-20">
		<div class="flex flex-col lg:flex-row gap-10">
			<div class="flex gap-3">
				<div><img src="/solidarity.png" alt="" /></div>
				<div class="flex flex-col">
					<div class="font-black text-2xl">Est. 2016</div>
					<div class="text-sm">by Tshepiso as a girl empowerment project.</div>
				</div>
			</div>
			<div class="flex gap-3">
				<div><img src="/idea.png" class="w-16" alt="" /></div>
				<div class="flex flex-col">
					<div class="font-black text-2xl">Inspired by</div>
					<div class="text-sm">1956 women march to parliament to fight injustice laws</div>
				</div>
			</div>
			<div class="flex gap-3">
				<div><img src="/leadership.png" class="w-16" alt="" /></div>
				<div class="flex flex-col">
					<div class="font-black text-2xl">Mission</div>
					<div class="text-sm">To provide tangible and non-tangible resources.</div>
				</div>
			</div>
		</div>
	</div>
</div>

<div
	class="px-6 lg:px-0 lg:mx-16 flex flex-col lg:flex-row gap-10 justify-center mb-10 items-center relative bg-gradient-to-b from-[#f79cb089]"
>
	<div class="text-3xl font-thin px-6 w-full lg:w-3/5 my-10 lg:my-0 text-center lg:text-right">
		&#10075;&#10075;Girl child education is a crucial aspect in the development of any society.
		Educating girls has been proven to have a multiplier effect that contributes to the overall
		progress and prosperity of the community. As a non-profit organization dedicated to promoting
		girl child education, we believe that every girl deserves an equal opportunity to receive a
		quality education.&#10076;&#10076;
		<span class="text-pink-600 text-xl italic">- Tshepiso, <b>Founder</b></span>
	</div>

	<div class="">
		<img
			src="/tshepiso.jpg"
			class="border-b-8 border-pink-600 w-64 rounded-2xl lg:rounded-none"
			alt="Tshepiso Tsogang"
		/>
	</div>
	<div class="w-full flex justify-center lg:w-1/5">
		<a ref="becomeYourDream" href="javascript:void(0)" class="text-3xl font-thin">
			Become your dream</a
		>
	</div>
</div>

<div class="min-h-96 py-10 mx-16 flex flex-col lg:flex-row gap-10">
	<img
		src="/sdg-banner.png"
		class="w-full lg:w-96 border-4 border-[#478bca]"
		alt="Sustainable Goals Development"
	/>
	<div class="self-center text-center font-black text-2xl text-[#478bca]">
		Our focus is on one of the United Nations' sustainable goals of equal and quality education
		targeting a girl child between the ages of 15 and 19.
	</div>
</div>

<section id="highlights" class="overflow-hidden text-gray-700 py-10">
	<div class="container px-5 py-2 mx-auto lg:pt-24 lg:px-32">
		<div class="flex flex-wrap -m-1 md:-m-2">
			<div class="flex flex-wrap w-1/2">
				<div class="w-1/2 p-1 md:p-2">
					<img
						alt="gallery"
						class="block object-cover object-center w-full h-full rounded-lg"
						src="/vicfalls1.jpg"
					/>
				</div>
				<div class="w-1/2 p-1 md:p-2">
					<img
						alt="gallery"
						class="block object-cover object-center w-full h-full rounded-lg"
						src="/shedecides1.jpg"
					/>
				</div>
				<div class="w-full p-1 md:p-2">
					<img
						alt="gallery"
						class="block object-cover object-center w-full h-full rounded-lg"
						src="/victoria-falls.jpg"
					/>
				</div>
			</div>
			<div class="flex flex-wrap w-1/2">
				<div class="w-full p-1 md:p-2">
					<img
						alt="gallery"
						class="block object-cover object-center w-full h-full rounded-lg"
						src="/shedecides2.jpg"
					/>
				</div>
				<div class="w-1/2 p-1 md:p-2">
					<img
						alt="gallery"
						class="block object-cover object-center w-full h-full rounded-lg"
						src="/betterworld.jpg"
					/>
				</div>
				<div class="w-1/2 p-1 md:p-2">
					<img
						alt="gallery"
						class="block object-cover object-center w-full h-full rounded-lg"
						src="/unlockres.jpg"
					/>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="min-h-[24-rem] py-10 px-20 lg:mx-16">
	<p class="text-3xl font-thin text-center">
		My objective is to plant a seed within the mind of a girl child to rely on the power of
		education to gain economic freedom and financial stability.
	</p>
	<div class="flex justify-center my-10">
		<h3 class="text-5xl font-thin">and I believe &hellip;</h3>
	</div>
	<div class="flex flex-col w-full gap-5">
		<div class="flex lg:flex-row flex-col w-full">
			<div class="lg:w-1/2 min-h-[4rem] bg-pink-500 flex justify-center items-center px-4 py-5">
				<p class="lg:font-black lg:text-lg text-center text-slate-200">
					That if you take a girl child to school, you educate a nation to school.
				</p>
			</div>
			<div class="lg:w-1/2 hidden lg:block">&nbsp;</div>
		</div>

		<div class="flex flex-col lg:flex-row w-full">
			<div class="w-1/2 h-16">&nbsp;</div>
			<div class="lg:w-1/2 h-16 bg-green-800 flex justify-center items-center px-4 py-5">
				<p class="text-center lg:font-black lg:text-lg text-slate-200">
					That education is a key to economic freedom & independence.
				</p>
			</div>
		</div>

		<div class="flex flex-col lg:flex-row w-full">
			<div class="lg:w-1/2 min-h-[4rem] bg-black flex justify-center items-center px-4 py-5">
				<p class="lg:font-black lg:text-lg text-center text-slate-200">
					That education is beyond the classroom. It is the power of having knowledge about your
					surrounding and empowering people around you.
				</p>
			</div>
			<div class="w-1/2 h-16">&nbsp;</div>
		</div>
	</div>
</section>

<div id="contribute" class="min-h-[24rem] bg-black mb-2 text-white">
	<div class="py-10 px-20 lg:mx-16 flex flex-col lg:flex-row items-center">
		<div class="w-full lg:w-3/5">
			<h2 class="font-black text-3xl mb-3" ref="supportUs">Support Us.</h2>
			<p class="text-slate-300 mb-8 text-sm font-light border-l-2 border-l-pink-600 px-3">
				As a non-profit organization, we rely on the support of donors like you to continue our
				mission of promoting girl child education. Whether you choose to donate, volunteer your
				time, or spread awareness about the importance of girl child education, every action counts.
				Join us in our mission to empower girls through education. Your donation or contributution
				can make a real difference in the lives of girls who otherwise would not have access to
				education.
			</p>

			<span class="font-black">With every contributution, you help to:</span>
			<ul class="list-disc pl-10 text-sm mt-3 text-slate-300">
				<li>Advocate for equal access to education</li>
				<li>
					Empower girls and their families with the knowledge and skills needed to make informed
					decisions about their education
				</li>
			</ul>
			<div class="flex gap-3 mt-6">
				<a
					href="."
					class="bg-white py-3 px-6 rounded-full text-black font-black hover:bg-slate-200"
				>
					Contribute
				</a>
				<div class="flex flex-col">
					<div class="text-sm mb-1 text-slate-300">Or give us a call on</div>
					<div class="text-yellow-700 font-bold">+(27) 81 738 1868</div>
				</div>
			</div>
		</div>
		<div class="w-full lg:w-2/5 mt-10 flex flex-col lg:justify-center items-center gap-6 relative">
			<img src="/take-away.png" class="absolute bottom-0 right-0" alt="" />
			<img src="/sanitary-pad.png" class="absolute left-0" alt="" />
			<img
				src="/book.png"
				class="absolute -top-10 lg:-top-14 right-0 lg:right-auto w-12 lg:w-16"
				alt=""
			/>
			<h3 class="font-black text-4xl text-yellow-400">Text Books</h3>
			<h3 class="font-black text-3xl text-pink-400">Sanitary Towels</h3>
			<h3 class="font-black text-4xl text-green-600">Food Packs</h3>
			<a href="." class="text-sm text-slate-300">and more..</a>
		</div>
	</div>
</div>
