<script setup>
import { RouterView } from 'vue-router'
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
</script>
<template>
  <div>
      <div class="min-h-screen bg-gray-100 dark:bg-gray-900">
        <Header />
        <main>
          <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
            <slot name="content"></slot>
            <RouterView />
          </div>
        </main>
        <Footer />
      </div>
  </div>
</template>
