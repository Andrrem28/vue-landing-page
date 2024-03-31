<template>
    <div style="background: url('src/assets/img/img-1.png'); height: 450px; background-repeat: no-repeat; background-size: cover;">
        <div class="container mx-auto h-full px-4 flex items-center justify-center">
            <div>
                <div class="text-center">
                    <h1 class="text-gray-200 text-3xl mb-1">Aonde deseja ir?</h1>
                    <p class="text-green-50">Escola o estado e a cidade com os melhores hoteis de cada região.</p>
                </div>

                <div class="mt-6">
                    <FormComponentVue />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import FormComponentVue from './FormComponent.vue'
    export default {
        name: "Banner",
        components: {
            FormComponentVue
        },
    };
</script>