<template>
    <div class="container max-w-5xl mx-auto px-2 py-20 flex justify-center">
        <form action="" class="grid grid-cols-2 gap-4 lg:grid-cols-3">
            <select class="bg-gray-50 px-3 py-2 border-gray-300 rounded text-gray-500">
                <option value="">Escolha o estado</option>
            </select>

            <select class="bg-gray-50 px-3 py-2 border-gray-300 rounded text-gray-500">
                <option value="">Escolha a cidade</option>
            </select>
            <button class="bg-blue-700 px-3 py-2 border-gray-300 rounded inline-flex justify-center items-center col-span-2 lg:col-span-1">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 mr-1">
                    <path fill-rule="evenodd" d="M9 3.5a5.5 5.5 0 1 0 0 11 5.5 5.5 0 0 0 0-11ZM2 9a7 7 0 1 1 12.452 4.391l3.328 3.329a.75.75 0 1 1-1.06 1.06l-3.329-3.328A7 7 0 0 1 2 9Z" clip-rule="evenodd" />
                </svg>
                Consultar hoteis
            </button>
        </form>
    </div>

</template>

<script>
    export default {
        name: "Form-Hotel"
    };
</script>