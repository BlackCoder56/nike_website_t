<script setup>
import { headerLogo } from '@/assets/images'; // No ?url
import { navLinks } from '@/constants' // imports array of nav links
</script>

<template>
  <header class="sm:px-16 px-8 py-8 absolute z-10 w-full">
    <nav class="flex justify-between items-center max-w-[1440px] mx-auto">
      <a href="/">
        <img 
          :src="headerLogo" 
          alt="Logo" 
          :style="{ width: '130px', height: '29px' }"
        />
      </a>

      <!-- nav links (desktop) -->
      <ul class="flex-1 flex justify-center items-center gap-16 max-lg:hidden">
        <li v-for="item in navLinks" :key="item.label">
          <a 
            :href="item.href"
            class="font-montserrat leading-normal text-lg text-slate-500"
          >
            {{ item.label }}
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>
