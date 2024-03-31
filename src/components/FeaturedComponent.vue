<template>
    <div class="container max-w-5xl mx-auto px-4 py-10 text-gray-600">
        <div class="flex flex-col-reverse lg:flex-row">
            <div class="lg:pr-14">
                <div class="text-sm text-gray-400 font-medium">Hotel em Destaque</div>
                <div class="text-2xl text-gray-500">Descrição</div>
                <div class="text-sm text-gray-500 font-medium mt-2">Hotel Qualidade 5 estrelas</div>
                <div class="text-sm text-gray-500 font-medium mt-3">
                    <p class="mb-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iste corporis officia alias vitae nobis quasi voluptatem veritatis dolore quis, odio suscipit praesentium accusantium sed consequuntur rem ad temporibus impedit cum?</p>
                </div>
                <div class="mt-3">
                    <ButtonFeaturedComponent />
                </div>
            </div>
            <div class="flex-shrink-0 lg:ml-auto pb-5 lg:mb-0">
                <img src="/src/assets/img/featured-img.png" alt="" width="450px">
            </div>
            
        </div>
    </div>
</template>

<script>
    import ButtonFeaturedComponent from './ButtonFeaturedComponent.vue';
    export default {
        name: "Featured",
        components: {
            ButtonFeaturedComponent
        },
    };
</script>