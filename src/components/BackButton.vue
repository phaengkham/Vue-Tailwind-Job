<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <Section>
        <div class="Container m-auto py-6 px-6">
            <RouterLink to="/jobs" class="text-green-500 hover:text-green-600 flex items-center">
                <div class=" flex items-center space-x-3">
                    <i class="pi pi-arrow-circle-left"></i>
                    <span>Back to Job Listings</span>
                </div>
            </RouterLink>
        </div>
    </Section>
</template>