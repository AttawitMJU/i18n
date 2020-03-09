<template>
  <v-layout>
    <v-flex class="text-center">
      <img src="/v.png" alt="Vuetify.js" class="mb-5" />
      <!-- <nuxt-link  :to="switchLocalePath('en')">
        English
      </nuxt-link>

      <nuxt-link  :to="switchLocalePath('th')">
        ไทย
      </nuxt-link> -->
      <blockquote class="blockquote">
        &#8220;{{ $t('quote') }}&#8221;
        <footer>
          <small>
            <em>&mdash;John Johnson</em>
          </small>
        </footer>
      </blockquote>
    </v-flex>
  </v-layout>
</template>
