<template>
    <div class="grid h-screen mx-auto place-items-center justify-center">
        <div class="max-w-3xl text-center">
            <h1 class="text-8xl mb-8 text-indigo-600 uppercase font-semibold tracking-tighter" v-if="title">{{ title }}</h1>
            <p class="text-3xl font-light text-indigo-400">This is the {{ desc }} page description.</p>
        </div>
    </div>
</template>
  
<script>
export default {
    props: {
        title: {
            type: String,
            required: true,
        },
        desc: {
            type: String,
            required: true,
        }
    }
}
</script>