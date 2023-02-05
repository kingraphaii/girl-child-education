<template>
  <div
    class="bg-slate-300 rounded-t-[50px] py-10 text-slate-700 font-light mt-10"
  >
    <div
      class="px-6 lg:px-0 lg:mx-16 flex flex-col lg:flex-row justify-between"
    >
      <div class="flex gap-10">
        <div>
          <span class="font-light text-sm text-center"
            >&#10075;&#10075;I want to plant a seed in a girl child that it does
            not matter where you come from, your dreams are valid. That is why I
            myself, standing here today.&#10076;&#10076; &mdash;
            <span class="text-xs">Tshepiso Tsogang</span>
          </span>
          <br />
        </div>
      </div>
      <div class="text-xs text-center mt-10 lg:mt-auto">
        <!-- <img
          src="/android-chrome-512x512.png"
          class="w-16 shadow-inner"
          alt=""
        /> -->
        Copyright &copy; {{ today.getFullYear() }} <b>Girl Child Education</b>.
        All Rights Reserved.
      </div>
    </div>
  </div>
  <div class="bg-black py-1 font-light">
    <div class="px-6 lg:px-0 text-right text-slate-50 lg:mx-16 text-sm">
      Connect with Tshepiso
      <a href=""> </a>
    </div>
  </div>
</template>

<script setup>
const today = new Date();
</script>
