<template>
    <div class="container max-w-5xl mx-auto px-4 ">
        <h3 class="text-2xl text-center text-gray-500 mb-8 font-medium">Tittle</h3>
        <GridImagesComponentVue />
   </div>
</template>
<script>
    import GridImagesComponentVue from './GridImagesComponent.vue';
    export default {
        name: "Hoteis",
        components: {
            GridImagesComponentVue,
        },
    };
</script>