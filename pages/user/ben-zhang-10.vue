<template>
    <h1>{{$nuxt.$route.name}}</h1>
</template>

<script>
export default {
    head() {
        return{
            title: $nuxt.$route.name,
            meta: [
                { hid: 'description', name: 'description', content: 'description' }
            ]
        }
    }
}
</script>