<template>
    <div class="w-full h-full">
        <div class="w-1/2 h-auto border border-gray-400 flex flex-col p-10 rounded shadow-lg mx-auto">
            <label for="email" class="text-xl fonot-semibold">Correo electronico</label>
            <input type="email" name="email" class="border-2 border-gray-600 p-2 rounded">
            <label for="pass" class="text-xl fonot-semibold">Password</label>
            <input type="password" name="pass" class="border-2 border-gray-600 p-2 rounded">
            <button class="px-3 py-3 bg-blue-600 text-white mt-4 w-40 rounded">Iniciar sesion</button>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>