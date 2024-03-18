<template>
  <div class="container mx-auto px-20">
    <div class="flex pt-5 gap-3">
      <img src="@/assets/img/icon/tg.svg" alt="" class="icon" />
      <img src="@/assets/img/icon/insta.svg" alt="" class="icon" />
      <img src="@/assets/img/icon/git.svg" alt="" class="icon" />
      <img src="" alt="" />
    </div>
    <div class="w-full flex justify-center text-center relative">
      <h2
        class="text-5xl font-bold pb-5 text-title flex justify-center nav__title mt-5"
      >
        About
      </h2>
    </div>
    <div
      class="flex text-white flex-wrap w-full justify-around mt-20 text-2xl gap-7 font-thin"
    >
      <p class="w-1/3 flex">
        <img src="@/assets/img/icon/right.svg" />
        &nbsp; Name: &nbsp;&nbsp;&nbsp;
        <span class="text-aqua font-bold">Nodirbek</span>
      </p>
      <p class="w-1/3 flex">
        <img src="@/assets/img/icon/right.svg" />
        &nbsp; Surname: &nbsp;&nbsp;&nbsp;
        <span class="text-aqua font-bold">Najmiddinov</span>
      </p>
      <p class="w-1/3 flex">
        <img src="@/assets/img/icon/right.svg" />
        &nbsp; Age: &nbsp;&nbsp;&nbsp;
        <span class="text-aqua font-bold">21</span>
      </p>
      <p class="w-1/3 flex">
        <img src="@/assets/img/icon/right.svg" />
        &nbsp; Occupation: &nbsp;&nbsp;&nbsp;
        <span class="text-aqua font-bold">Developer</span>
      </p>
      <p class="w-1/3 flex">
        <img src="@/assets/img/icon/right.svg" />
        &nbsp; Live: &nbsp;&nbsp;&nbsp;
        <span class="text-aqua font-bold">Tashkent</span>
      </p>
      <p class="w-1/3 flex">
        <img src="@/assets/img/icon/right.svg" />
        &nbsp; From: &nbsp;&nbsp;&nbsp;
        <span class="text-aqua font-bold">Bukhara</span>
      </p>
    </div>
  </div>
</template>
<script setup></script>
<style lang="css">
.icon {
  filter: invert(80%) brightness(80%);
  width: 30px;
}
</style>
