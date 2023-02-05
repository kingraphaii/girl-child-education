<template>
  <div
    class="bg-gradient-to-r from-pink-500 text-base font- w-full p-2 px-6 lg:px-16 text-slate-100 -tracking-wide"
  >
    Never dim your light!
  </div>
  <nav
    class="bg-white px-6 lg:px-16 border-pink-800 shadow-2xl py-7 flex items-center justify-between"
  >
    <div
      class="relative after:text-xs after:font-bold after:-right-4 after:content-['by\a0tshepiso\a0tsogang'] after:text-pink-600 after:absolute after:-bottom-3"
    >
      <a href="#" class="text-4xl font-thin tracking-tight text-bold"
        ><span class="font-black text-pink-600">Girl Child</span> Education</a
      >
    </div>
    <div
      class="md:flex hidden items-center justify-center space-x-4 text-lg font-extralight"
    >
      <a
        href="#our-mission"
        class="px-3 py-2 leading-5 text-lg hover:bg-pink-400 hover:text-white focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out"
        >Our Mission</a
      >
      <a
        href="#highlights"
        class="px-3 py-2 leading-5 hover:bg-pink-400 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out hover:text-white"
        >Highlights</a
      >
      <a
        href="#contribute"
        class="px-3 py-2 leading-5 hover:bg-pink-400 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out hover:text-white"
        >Get Involved</a
      >
      <a
        href="#contribute"
        class="px-5 py-3 leading-5 bg-pink-600 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out text-white"
        >Contribute</a
      >
    </div>
  </nav>
  <!-- after:absolute after:left-0 after:w-1/2 after:content-[''] after:text-xs after:bottom-0 after:border-b after:border-white -->
  <section
    class="bg-cover px-6 lg:px-0 lg:mx-16 lg:bg-left-top h-[82vh] relative bg-center"
    style="background-image: url('/amevi-wisdom.jpg')"
  >
    <div
      class="mx-auto left-0 p-5 top-0 lg:p-6 bg-gradient-to-b from-pink-500 lg:bg-pink-500 selection:bg-black absolute text-black w-4/5 lg:w-1/3 rounded-br-3xl after:absolute after:content-[''] sm:after:bottom-0 after:w-2/5 after:border-b-8 after:left-0 after:border-white"
    >
      <h3
        class="text-3xl lg:text-5xl font-light lg:font-thin text-slate-200 relative mb-8"
      >
        Every girl child deserves
        <span ref="typedHero" class="font-black"></span>
      </h3>
      <p class="text-lg mt-5 text-slate-200 mb-8 lg:font-thin relative">
        With your support, we can provide education to girls who may not have
        had the opportunity otherwise – altering the trajectory of their lives,
        the lives of their children and the future of their communities.
      </p>
    </div>

    <div
      class="mx-auto bg-gradient-to-t from-pink-500 lg:rounded-tl-[4.8rem] right-0 p-5 bottom-0 lg:p-8 lg:bg-pink-500 selection:bg-black absolute text-black w-4/5 lg:w-1/3 after:absolute after:content-[''] sm:after:top-0 after:w-2/5 after:border-b-8 after:right-0 after:border-white"
    >
      <h3
        id="h3"
        class="text-3xl lg:text-3xl font-black lg:font-bold text-slate-200 relative"
      >
        Objective.
      </h3>
      <p class="text-lg mt-5 text-slate-200 mb-8 lg:font-thin relative">
        For girl child to depend on education for economic freedom, to take and
        keep a girl in school with tools that will eliminate barriers that will
        hinder with their education.
      </p>
    </div>
  </section>

  <div id="our-mission" class="h-72 bg-gradient-to-t from-[#f79cb089]">
    <div
      class="h-full flex justify-center items-center px-6 lg:px-0 lg:mx-16 mt-20"
    >
      <div class="flex flex-col lg:flex-row gap-10">
        <div class="flex gap-3">
          <div><img src="/solidarity.png" alt="" /></div>
          <div class="flex flex-col">
            <div class="font-black text-2xl">Est. 2016</div>
            <div class="text-sm">
              by Tshepiso as a girl empowerment project.
            </div>
          </div>
        </div>
        <div class="flex gap-3">
          <div><img src="/idea.png" class="w-16" alt="" /></div>
          <div class="flex flex-col">
            <div class="font-black text-2xl">Inspired by</div>
            <div class="text-sm">
              1956 women march to parliament to fight injustice laws
            </div>
          </div>
        </div>
        <div class="flex gap-3">
          <div><img src="/leadership.png" class="w-16" alt="" /></div>
          <div class="flex flex-col">
            <div class="font-black text-2xl">Mission</div>
            <div class="text-sm">
              To provide tangible and non-tangible resources.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div
    class="px-6 lg:px-0 lg:mx-16 flex flex-col lg:flex-row gap-10 justify-center mb-10 items-center relative bg-gradient-to-b from-[#f79cb089]"
  >
    <div
      class="text-3xl font-thin px-6 w-full lg:w-3/5 my-10 lg:my-0 text-center lg:text-right"
    >
      &#10075;&#10075;Girl child education is a crucial aspect in the
      development of any society. Educating girls has been proven to have a
      multiplier effect that contributes to the overall progress and prosperity
      of the community. As a non-profit organization dedicated to promoting girl
      child education, we believe that every girl deserves an equal opportunity
      to receive a quality education.&#10076;&#10076;
      <span class="text-pink-600 text-xl italic"
        >- Tshepiso, <b>Founder</b></span
      >
    </div>

    <div class="">
      <img
        src="/tshepiso.jpg"
        class="border-b-8 border-pink-600 w-64 rounded-2xl lg:rounded-none"
        alt="Tshepiso Tsogang"
      />
    </div>
    <div class="w-full flex justify-center lg:w-1/5">
      <a
        ref="becomeYourDream"
        href="javascript:void(0)"
        class="text-3xl font-thin"
      >
        Become your dream</a
      >
    </div>
  </div>

  <div class="min-h-96 py-10 mx-16 flex flex-col lg:flex-row gap-10">
    <img
      src="/sdg-banner.png"
      class="w-full lg:w-96 border-4 border-[#478bca]"
      alt=""
    />
    <div class="self-center text-center font-black text-2xl text-[#478bca]">
      Our focus is on one of the United Nations' sustainable goals of equal and
      quality education targeting a girl child between the ages of 15 and 19.
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

  <div id="contribute" class="min-h-[24rem] bg-black mb-2 text-white">
    <div class="py-10 px-20 lg:mx-16 flex flex-col lg:flex-row items-center">
      <div class="w-full lg:w-3/5">
        <h2 class="font-black text-3xl mb-3" ref="supportUs">Support Us.</h2>
        <p
          class="text-slate-300 mb-8 text-sm font-light border-l-2 border-l-pink-600 px-3"
        >
          As a non-profit organization, we rely on the support of donors like
          you to continue our mission of promoting girl child education. Whether
          you choose to donate, volunteer your time, or spread awareness about
          the importance of girl child education, every action counts. Join us
          in our mission to empower girls through education. Your donation or
          contributution can make a real difference in the lives of girls who
          otherwise would not have access to education.
        </p>

        <span class="font-black">With every contributution, you help to:</span>
        <ul class="list-disc pl-10 text-sm mt-3 text-slate-300">
          <li>Advocate for equal access to education</li>
          <li>
            Empower girls and their families with the knowledge and skills
            needed to make informed decisions about their education
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
      <div
        class="w-full lg:w-2/5 mt-10 flex flex-col lg:justify-center items-center gap-6 relative"
      >
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

  <Footer></Footer>
</template>

<script>
import Typed from "typed.js";

export default {
  mounted() {
    const options = {
      strings: [
        "to participate in economic development.",
        "learning opportunities.",
        "an equal opportunity to receive quality education.",
      ],
      typeSpeed: 40,
      loopCount: 3,
      loopDelay: 10000,
      loop: true,
    };
    const options2 = {
      strings: ["never dim your light.", "become your dream."],
      typeSpeed: 40,
      showCursor: false,
      loopCount: 3,
      loopDelay: 10000,
      loop: true,
    };

    this.typed = new Typed(this.$refs.typedHero, options);
    this.typed2 = new Typed(this.$refs.becomeYourDream, options2);
  },
};
</script>
