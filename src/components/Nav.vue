<script setup>
import headerLogo from '@/assets/images/headerlogo.svg?url';
import { hamburger } from '@/assets/icons';
</script>

<template>
  <header class="sm:px-16 px-8 py-8 absolute z-10 w-full">
    <nav>
      <a href="/">
        <img 
        :src="headerLogo" 
        alt="Logo" 
        :style="
        {
          width:'130px',
          height:'29px'
        }" />
      </a>
    </nav>
  </header>
</template>
