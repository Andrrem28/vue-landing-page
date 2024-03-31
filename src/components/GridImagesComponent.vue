<template>
    <div class="md:grid md:grid-cols-4 md:grid-rows-2 md:gap-6 space-y-6 md:space-y-0">
        <div class="relative md:col-span-2 md:row-span-2 rounded-lg overflow-hidden">
            <div class="absolute bottom-0 pl-3 pb-3 text-white font-bold z-20">
                Hotel Resort 1
            </div>
            <img src="/src/assets/img/image-shadow.png" alt="" class="absolute bottom-0 left-0 right-0 h-20 z-10">
            <img src="/src/assets/img/hotel-1.jpeg" alt="" class="w-full h-full object-cover">
        </div>
        <div class="relative md:col-span-2 md:h-40 rounded-lg overflow-hidden">
            <div class="absolute bottom-0 pl-3 pb-3 text-white font-bold z-20">
                Hotel Resort 2
            </div>
            <img src="/src/assets/img/image-shadow.png" alt="" class="absolute bottom-0 left-0 right-0 h-20 z-10">
            <img src="/src/assets/img/hotel-2.jpeg" alt="" class="w-full h-full object-cover">
        </div>
        <div class="relative rounded-lg overflow-hidden">
            <div class="absolute bottom-0 pl-3 pb-3 text-white font-bold z-20">
                Hotel Resort 3
            </div>
            <img src="/src/assets/img/image-shadow.png" alt="" class="absolute bottom-0 left-0 right-0 h-20 z-10">
            <img src="/src/assets/img/hotel-3.jpeg" alt="" class="w-full h-full object-cover">
        </div>
        <div class="relative rounded-lg overflow-hidden">
            <div class="absolute bottom-0 pl-3 pb-3 text-white font-bold z-20">
                Hotel Resort 4
            </div>
            <img src="/src/assets/img/image-shadow.png" alt="" class="absolute bottom-0 left-0 right-0 h-20 z-10">
            <img src="/src/assets/img/hotel-4.jpeg" alt="" class="w-full h-full object-cover">
        </div>
    </div>
</template>
<script>
    export default {
        name: "GridImages",
    };
</script>