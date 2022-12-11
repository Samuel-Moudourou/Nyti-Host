<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HomeView from './views/HomeView.vue';
</script>

<template>
<div class="dark:bg-gray-900">
    <RouterView v-slot="{Component}">
        <Transition name="page" mode="out-in">
            <Component :is="Component" />
        </Transition>
    </RouterView>
</div>
</template>

<style>
.page-enter-active,
.page-leave-active {
    transition: 600ms ease all;
}

.page-enter-from,
.page-leave-to{
    opacity: 0;
}
</style>

