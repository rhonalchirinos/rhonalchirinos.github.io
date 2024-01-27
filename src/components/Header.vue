<script setup>
import { ref, onMounted } from 'vue'
import Terminal from "./Terminal.vue";

const show = ref(false)

function active() {
    show.value = true
}

</script>

<template>
    <header class="mt-12 px-4 sm:px-12 mb-12">
        <div class="items-center mb-12">
            <ol class="text-sm leading-6">
                <li class="font-semibold">
                    <p class="text-3xl font-semibold text-gray-900 mb-4">
                        RHONAL CHIRINOS...... <br> <br>
                        <span @click="active"> 👨🏽‍💻 </span>
                    </p>
                </li>
            </ol>
        </div>
        <div v-if="show">
            <Terminal />
        </div>
    </header>
</template>