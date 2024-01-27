<script setup>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Skill from "./components/Skill.vue";
import Education from "./components/Education.vue";
import Pdf from "./components/Pdf.vue";

</script>

<template>
    <div class="container mx-auto sm:px-0 md:px-4 lg:px-2 xl:px-12  ">
        <Header />
        <Pdf />
        <Education />
        <Skill />
        <Footer />
    </div>
</template>

<style scoped></style>
