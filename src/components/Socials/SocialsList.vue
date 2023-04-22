<template>
  <section-page class="border-y-2">
    <div class="flex flex-wrap justify-between px-4 gap-x-px">
      <a
        v-for="social of socials"
        :href="social.link"
        target="_blank"
        class="font-light text-gray-400 text-[0.9em] hover:text-cyan-500 hover:font-thin"
        >{{ social.name.toUpperCase() }}</a
      >
    </div>
  </section-page>
</template>

<script setup>
import { ref, reactive } from 'vue';

import SectionPage from '../UI/SectionPage.vue';
import Social from './Social.vue';

const socials = reactive([
  { name: 'github', link: 'https://github.com/bsplabs?tab=repositories' },
  { name: 'gitlab', link: '' },
  {
    name: 'linked in',
    link: 'https://www.linkedin.com/in/sittikorn-prasanlak-843158171/',
  },
  {
    name: 'resume',
    link: 'https://docs.google.com/document/d/12s6b4I3QFRryUzwYio99GLpWvGIi26N5HbDFLEXf6eo/edit?usp=sharing',
  },
]);
</script>
