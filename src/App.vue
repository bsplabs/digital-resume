<template>
  <div class="max-w-[700px] my-0 mx-auto p-[1em]">
    <SectionPage class="flex items-center justify-center gap-16 pt-12">
      <img
        src="./assets/images/profile.jpg"
        alt="Profile"
        class="w-[150px] h-[150px] object-cover rounded-[50%]"
      />
      <div class="box-border leading-6 text-white">
        <h1 class="text-5xl leading-[1em]">Sittikorn Prasanlak</h1>
        <p class="font-light text-[1em] text-gray-400 mt-4 text-right">
          Full Stack Developer at <a href="https://www.lalabo.co.th/">Lalabo</a>
        </p>
        <p class="mt-4 text-right">👉 bsplabs@gmail.com</p>
      </div>
    </SectionPage>

    <socials-list />

    <section-page class="pt-8">
      <h2 class="my-4 text-white font-2xl">Skill & Qualifications</h2>
      <ul class="">
        <li class="text-[1em] text-gray-400">
          ✔️ 4 Years experience with front &amp; backend development
        </li>
        <li class="text-[1em] text-gray-400">
          ✔️ 2 Years experience with PHP and VueJS stack
        </li>
        <li class="text-[1em] text-gray-400">
          ✔️ 4 Years experience with front &amp; backend development
        </li>
        <li class="text-[1em] text-gray-400">
          ✔️ 4 Years experience with front &amp; backend development
        </li>
      </ul>
    </section-page>

    <section-page>
      <h2 class="my-4 text-white font-2xl">Tech Stack</h2>
      <div class="flex flex-wrap gap-4 text-[0.9em] text-white">
        <div class="p-3 border-2 border-gray-600 rounded">
          <span>php, vuejs, mysql</span>
        </div>
        <div class="p-3 border-2 border-gray-600 rounded">
          <span>ruby on Rails, react, coffeescript</span>
        </div>
        <div class="p-3 border-2 border-gray-600 rounded">
          <span>nodejs, typescript</span>
        </div>
      </div>
    </section-page>
  </div>
</template>

<script setup>
import SectionPage from './components/UI/SectionPage.vue';
import SocialsList from './components/Socials/SocialsList.vue';
</script>
