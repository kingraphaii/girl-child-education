<template>
  <div
    class="bg-pink-800 text-base font- w-full p-2 px-6 lg:px-16 text-slate-100 -tracking-wide"
  >
    Never dim your light!
  </div>
  <nav
    class="bg-white px-6 lg:px-16 border-pink-800 shadow-2xl py-7 flex items-center justify-between"
  >
    <div
      class="relative after:text-xs after:font-bold after:-right-4 after:content-[&quot;by\a0tshepiso\a0tsogang&quot;] after:text-pink-600 after:absolute after:-bottom-3"
    >
      <a href="#" class="text-4xl font-thin tracking-tight text-bold"
        ><span class="font-black text-pink-600">Girl Child</span> Education</a
      >
    </div>
    <div
      class="md:flex hidden items-center justify-center space-x-4 text-lg font-extralight"
    >
      <a
        href="#"
        class="px-3 py-2 leading-5 text-lg hover:bg-pink-400 hover:text-white focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out"
        >Our Mission</a
      >
      <a
        href="#"
        class="px-3 py-2 leading-5 hover:bg-pink-400 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out hover:text-white"
        >How We Help?</a
      >
      <a
        href="#"
        class="px-3 py-2 leading-5 hover:bg-pink-400 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out hover:text-white"
        >Get Involved</a
      >
      <a
        href="#"
        class="px-5 py-3 leading-5 bg-pink-600 focus:outline-none focus:bg-pink-400 transition duration-150 ease-in-out text-white"
        >DONATE</a
      >
    </div>
  </nav>
  <!-- after:absolute after:left-0 after:w-1/2 after:content-[''] after:text-xs after:bottom-0 after:border-b after:border-white -->
  <section
    class="bg-cover px-6 lg:px-0 lg:mx-16 lg:bg-left-top h-[82vh] relative bg-center"
    style="background-image: url('/amevi-wisdom.jpg')"
  >
    <div
      class="mx-auto shadow-2xl left-0 p-5 top-0 lg:p-10 bg-pink-500 selection:bg-black absolute text-black w-4/5 lg:w-1/3 rounded-br-3xl after:absolute after:content-[''] sm:after:bottom-0 after:w-2/5 after:border-b-8 after:left-0 after:border-white"
    >
      <h3
        class="text-3xl lg:text-5xl font-light lg:font-thin text-slate-200 relative mb-8"
      >
        Every girl child deserves
        <span ref="typedHero" class="font-bold"></span>
      </h3>
      <p class="text-lg mt-5 text-slate-200 mb-8 font-thin relative">
        With your support, we can provide education to girls who may not have
        had the opportunity otherwise – altering the trajectory of their lives,
        the lives of their children and the future of their communities.
      </p>
    </div>

    <div
      class="mx-auto rounded-tl-[4.8rem] right-0 p-5 bottom-0 lg:p-8 bg-pink-500 selection:bg-black absolute text-black w-4/5 lg:w-1/3 after:absolute after:content-[''] sm:after:top-0 after:w-2/5 after:border-b-8 after:right-0 after:border-white"
    >
      <h3
        id="h3"
        class="text-3xl lg:text-3xl font-normal lg:font-bold text-slate-200 relative"
      >
        Objective.
      </h3>
      <p class="text-lg mt-5 text-slate-200 mb-8 font-thin relative">
        A girl child to depend on education for economic freedom:To take and
        keep a girl in school with tools that will eliminate barriers that will
        hinder with their education.
      </p>
    </div>
  </section>

  <div class="h-72 bg-gradient-to-t from-[#f79cb089]">
    <div
      class="h-full flex justify-center items-center px-6 lg:px-0 lg:mx-16 mt-20"
    >
      <div class="flex gap-10">
        <div class="flex gap-3">
          <div><img src="/solidarity.png" alt="" /></div>
          <div class="flex flex-col">
            <div class="font-black">Est. 2016</div>
            <div class="text-sm">
              by Tshepiso as a girl empowerment project.
            </div>
          </div>
        </div>
        <div class="flex gap-3">
          <div><img src="/idea.png" class="w-16" alt="" /></div>
          <div class="flex flex-col">
            <div class="font-black">Inspired by</div>
            <div class="text-sm">
              1956 women march to parliament to fight injustice laws
            </div>
          </div>
        </div>
        <div class="flex gap-3">
          <div><img src="/leadership.png" class="w-16" alt="" /></div>
          <div class="flex flex-col">
            <div class="font-black">Mission</div>
            <div class="text-sm">
              To provide tangible and non-tangible resources.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div
    class="px-6 lg:px-0 lg:mx-16 flex gap-10 justify-center mb-5 items-center h-80 relative bg-gradient-to-b from-[#f79cb089]"
  >
    <div class="text-3xl font-thin px-6 w-3/5 text-right">
      &#10075;&#10075;Girl child education is a crucial aspect in the
      development of any society. Educating girls has been proven to have a
      multiplier effect that contributes to the overall progress and prosperity
      of the community. As a non-profit organization dedicated to promoting girl
      child education, we believe that every girl deserves an equal opportunity
      to receive a quality education.&#10076;&#10076;
      <span class="text-pink-600 text-base italic"
        >- Tshepiso, <b>Founder</b></span
      >
    </div>

    <div class="flex justify-cednter">
      <img
        src="/tshepiso.jpg"
        class="border-b-8 border-pink-600 w-64"
        alt="Tshepiso Tsogang"
      />
    </div>
    <div class="w-1/5">
      <a ref="becomeYourDream" href="" class="text-3xl font-thin">
        Become your dream</a
      >
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
      ],
      typeSpeed: 90,
      loopCount: 3,
      loopDelay: 10000,
    };
    const options2 = {
      strings: ["never dim your light.", "become your dream."],
      typeSpeed: 40,
      loopCount: Infinity,
    };

    this.typed = new Typed(this.$refs.typedHero, options);
    this.typed2 = new Typed(this.$refs.becomeYourDream, options2);
  },
};
</script>
