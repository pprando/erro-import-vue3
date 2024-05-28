<template>
    <TheHeader
        v-show="showHeader"
    />
         <img   alt="Vue logo"
        src="./assets/logo.png">
        <!-- v-show=""
        v-if=""
        v-else-if=""
        v-else  -->
        <HelloWord msg="Welcome to your Vue.js App"/>
</template>

<script>
import HelloWord from './HelloWorld.vue';
import TheHeader from './components/TheHeader';

export default {
    name: 'App',
    components: {
        HelloWord,
        TheHeader
    }
}
</script>

<style>

</style>