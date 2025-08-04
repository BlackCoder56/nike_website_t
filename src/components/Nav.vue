<script setup>
import headerLogo from '@/assets/images/headerlogo.svg?url';
import { hamburger } from '@/assets/icons';
</script>

<template>
  <header class="padding-x py-8 absolute z-10 w-full">
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
