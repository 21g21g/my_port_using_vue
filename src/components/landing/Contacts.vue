<script setup>
import { ref } from "vue";
import Textarea from 'primevue/textarea';
import InputText from 'primevue/inputtext';


</script>
<template>
<div class="min-h-screen flex justify-center items-center bg-black">
    <div class="bg-white shadow-lg rounded-xl p-6 w-full max-w-lg flex flex-col gap-6 text-center">
        <h2 class="text-2xl font-bold text-gray-800">Get in Touch</h2>
        
        <div class="flex flex-col w-full items-center gap-4 md:flex-row md:justify-center">
            <!-- Phone Contact -->
            <div class="flex items-center gap-3 text-lg transition-transform transform hover:scale-105">
                <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" class="text-blue-500" viewBox="0 0 24 24">
                    <path fill="currentColor" stroke="currentColor" stroke-width="2" d="M8 3c0.5 0 2.5 4.5 2.5 5c0 1 -1.5 2 -2 3c-0.5 1 0.5 2 1.5 3c0.39 0.39 2 2 3 1.5c1 -0.5 2 -2 3 -2c0.5 0 5 2 5 2.5c0 2 -1.5 3.5 -3 4c-1.5 0.5 -2.5 0.5 -4.5 0c-2 -0.5 -3.5 -1 -6 -3.5c-2.5 -2.5 -3 -4 -3.5 -6c-0.5 -2 -0.5 -3 0 -4.5c0.5 -1.5 2 -3 4 -3Z" />
                </svg>
                <a href="tel:+251984198343" class="text-blue-500 font-bold hover:underline">+251 984198343</a>
            </div>
            
            <!-- Email Contact -->
            <div class="flex items-center gap-3 text-lg transition-transform transform hover:scale-105">
                <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" class="text-blue-500" viewBox="0 0 24 24">
                    <path fill="currentColor" d="M4 5h16c0.55 0 1 0.45 1 1v12c0 0.55 -0.45 1 -1 1h-16c-0.55 0 -1 -0.45 -1 -1v-12c0 -0.55 0.45 -1 1 -1Z" />
                    <path fill="none" stroke="currentColor" stroke-width="2" d="M3 6.5l9 5.5l9 -5.5" />
                </svg>
                <a href="mailto:assegagebeyehu21@gmail.com" class="text-blue-500 font-bold hover:underline">assegagebeyehu21@gmail.com</a>
            </div>
        </div>
    </div>
</div>
</template>