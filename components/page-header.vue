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
    #backlink {
        float: right;
        width: 3rem;
        height: 3rem;
        border-radius: 50%;
    }
    
    @media only screen and (max-width: 420px) {
        #backlink {
            display: none;
        }
    }
</style>