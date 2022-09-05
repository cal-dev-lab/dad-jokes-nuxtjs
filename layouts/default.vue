<template>
    <div>
        <Navbar />
        <nuxt />
    </div>
    
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
    head() {
        return {
            meta: [
                {
                    hid: "description",
                    name: "description",
                    content: "Best place for dad jokes.",
                }
            ],
            link: [
                // Dynamic canonical URL
                {
                    rel: "canonical",
                    href: "https://illustrious-moxie-b1844f.netlify.app" + this.$route.path
                }
            ]
        };
    },
    components: { Navbar }
}
</script>