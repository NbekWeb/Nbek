<template>
  <div id="home">
    <div class="border">
      <div class="stars">
        <section class="sectiona">
          <span class="star"></span>
        </section>
      </div>
      <div class="twin"></div>
    </div>
    <div class="container mx-auto mt-10 px-20 ">
      <div class="flex items-center justify-between">
        <router-link to="/">
          <img src="@/assets/img/logo.png" alt="my logo" width="70px" />
        </router-link>
        <nav class="flex gap-7 text-white text-xl font-bold">
          <router-link to="/">Home</router-link>
          <router-link to="#about">About</router-link>
          <router-link to="#skil">Skills</router-link>
          <router-link to="#work">Work</router-link>
          <router-link to="#contact">Contact</router-link>
        </nav>
      </div>
      <div class="flex justify-between items-center mt-10 ">
        <div>
          <h2 class="header__title italic mb-4">HI!</h2>
          <p class="text-3xl text-bisque mb-6">
            I am a simple <span class="text-aqua">web developer</span>
          </p>
          <a
            href="#d"
            class="bg-btn p-2 rounded-md text-white opacity-70 hover:opacity-100"
            >Resume</a
          >
        </div>
        <div class="bg-white header__left">
          <img src="@/assets/img/me.jpg" class="header__img" />
        </div>
      </div>
    </div>
  </div>
</template>
<script setup></script>
