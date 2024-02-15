<script setup>
import BrandLogo from '@/components/icons/BrandLogo.vue';
import LightDarkModeSwitch from '@/components/LightDarkModeSwitch.vue';
</script>
<template>
    <nav class="border-gray-200 bg-gray-50 dark:bg-gray-800 dark:border-gray-700">
        <div class="flex flex-wrap items-center justify-between  p-8">
            <div class="items-left">
                <BrandLogo />
            </div>
            <div class="items-right">
                <LightDarkModeSwitch />
            </div>
        </div>
    </nav>    
</template>
