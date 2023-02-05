<template>
  <div class="bg-pink-600 rounded-t-[50px] py-10 text-slate-100 font-light">
    <div class="px-6 lg:px-0 lg:mx-16 flex justify-between">
      <div class="flex gap-10">
        <div>
          <b class="font-bold">South Africa</b> <br />
          <div class="text-sm">
            <div class="mt-3">10a Lant Street,</div>
            <div>Johannesburg</div>
            <div class="mt-3 underline">+27 690 8211 78</div>
          </div>
        </div>
        <div>
          <b class="font-bold">Zimbabwe</b> <br />
          <div class="text-sm">
            <div class="mt-3">63 Clyde Rd,</div>
            <div>Eastlea</div>
            <div class="mt-3 underline">+263 712 194 667</div>
          </div>
        </div>
      </div>
      <div class="text-sm">
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
  <div class="bg-pink-500 py-1 font-light">
    <div class="px-6 lg:px-0 text-right text-slate-50 lg:mx-16 text-sm">
      Website designed with &hearts; by <a href=".">Bytes & Bots</a>
    </div>
  </div>
</template>

<script setup>
const today = new Date();
</script>
