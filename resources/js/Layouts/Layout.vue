<script setup>
import Main from "@/Layouts/Main.vue";
import Header from "@/Layouts/Header.vue";
import Nav  from "@/Layouts/Nav.vue";
import Footer from "@/Layouts/Footer.vue";


</script>

<template>
    <Header />
    <Nav />
    <main class="h-65v bg-main">
        <slot></slot>
    </main>
    <Footer />

</template>

<style scoped>

</style>
