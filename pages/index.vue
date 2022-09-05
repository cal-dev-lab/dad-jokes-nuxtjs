<template>
  <PageScreen title="Welcome!" desc="home" />
</template>

<script>
import PageScreen from '~/components/PageScreen.vue';
export default {
    name: "Home page",
    head() {
        return {
            title: "Dad Jokes Central"
        };
    },
    components: { PageScreen }
}
</script>
