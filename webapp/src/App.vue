<template>
    <NavBar />
    <router-view />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import NavBar from './components/NavBar.vue';

export default defineComponent({
    name: 'App',
    components: {
        NavBar,
    },
});
</script>

<style>
/* Show it is fixed to the top */
body {
    padding-bottom: 1rem;
    padding-top: 4.5rem;
}
</style>
