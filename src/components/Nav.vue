<script setup>
import headerLogo from '@/assets/images/headerlogo.svg?url';
</script>

<template>
  <header class="padding-x py-8 absolute z-10 w-full">
    <nav>
      <a href="/">
        <img :src="headerLogo" alt="Logo" class="w-32 h-auto" />
      </a>
    </nav>
  </header>
</template>
