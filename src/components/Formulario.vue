<script setup>

</script>


<template>
    <div class="md:w-1/2">
        <h2 class="font-black text-3xl text-center">Seguimiento pacientes</h2>

        <p class="text-lg mt-5 text-center mb-10">
            Añade pacientes y
            <span class="text-indigo-600 font-bold">adminístralos</span>
        </p>

        <form class="bg-white shadow-md rounded-lg py-10 px-5 mb-10" action="">
            <div class="mb-5">
                <label for="mascota" class="block text-gray-700 uppercase font-bold">
                    Nombre Mascota
                </label>
                <input placeholder="Nombre de la mascota" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                    id="mascota" type="text">
            </div>

            <div class="mb-5">
                <label for="propietario" class="block text-gray-700 uppercase font-bold">
                    Nombre Propietario
                </label>
                <input placeholder="Nombre del propietario" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
                    id="propietario" type="text">
            </div>

            <div class="mb-5">
                <label for="email" class="block text-gray-700 uppercase font-bold">
                    Email
                </label>
                <input placeholder="Email" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md" id="email"
                    type="email">
            </div>

            <div class="mb-5">
                <label for="alta" class="block text-gray-700 uppercase font-bold">
                    Alta
                </label>
                <input class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md" id="alta"
                    type="date">
            </div>

            <div class="mb-5">
                <label for="sintomas" class="block text-gray-700 uppercase font-bold">
                    sintomas
                </label>
                <textarea placeholder="Describe los sintomas del paciente" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md h-40" id="sintomas"
                    type="text" 
                />
            </div>

            <input type="submit" class="bg-indigo-600 w-full p-3 text-white uppercase font-bold hover:bg-indigo-700 cursor-pointer transition-colors" value="Registrar paciente">

        </form>
    </div>
</template>

