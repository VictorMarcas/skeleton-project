<template>
    <div class="flex items-center justify-center w-full h-screen bg-gray-300">
        <div class="text-xl font-bold text-white uppercase">{{ message }}</div>
    </div>
</template>

<script>
    export default {
        name: 'app',
        data () {
            return {
                message: 'Hola Mundo'
            }
        }
    }
</script>
