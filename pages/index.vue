<template>
    <section class="container">

    </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
    components: {
        Logo
    },
    head() {
        return {
                script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
        };
    },
}
</script>

<style>

.container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}
</style>
