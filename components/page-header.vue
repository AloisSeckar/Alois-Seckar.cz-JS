<template>
    <h1>{{ title }} <nuxt-link to="/" title="Alois-Seckar.cz"><img id="backlink" src="~/assets/profile.webp" alt="Index"></nuxt-link></h1>
</template>

<script>
    export default {
        props: {
            title: {type: String, default: "Alois-Seckar.cz"}
        }
    }
</script>

<style>
    h1 {
        font-family: 'Courier New', monospace;
        font-size: 3rem;
        font-weight: normal;
    }

    #backlink {
        float: right;
        width: 3rem;
        height: 3rem;
        border-radius: 50%;
    }
</style>