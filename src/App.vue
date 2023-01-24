<script>
import AppHeader from '@/components/AppHeader.vue';

export default {
    components: {
        AppHeader,
    },
};
</script>

<template>
    <div class="app">
        <AppHeader />

        <div class="mt-3 container">
            <router-view />
        </div>
    </div>
</template>

<style>
.page {
    max-width: 400px;
    margin: auto;
}
</style>
