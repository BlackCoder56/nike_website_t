<script>
    // import { headerLogo } from '@/assets/images';
    import headerLogo from '@/assets/images/customer1.jpeg';
    // import { hamburger } from '@/assets/icons';
</script>

<template>
    <header class="padding-x py-8 absolute z-10 w-full">
        <nav>
            <a href="/">
                <img :src='headerLogo' alt="Logo">
            </a>
        </nav>
    </header>
</template>