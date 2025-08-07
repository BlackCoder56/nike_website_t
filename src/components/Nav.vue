<script setup>
import headerLogo from '@/assets/images/headerlogo.svg?url';
import { hamburger } from '@/assets/icons';
</script>

<template>
  <header class="sm:px-16 px-8 py-8 absolute z-10 w-full">
    <nav class="flex justify-between items-center max-w-[1440px] mx-auto">
      <a href="/">
        <img 
        :src="headerLogo" 
        alt="Logo" 
        :style="
        {
          width:'130px',
          height:'29px'
        }" />
        <ul class="flex-1 flex justify-center items-center gap-16 max-lg:hidden">
          
        </ul>
      </a>
    </nav>
  </header>
</template>
