<script setup>

</script>

<template>
    <header class="hidden lg:flex h-15v bg-header flex flex-row justify-center items-center">
        <img class="w-1/5 max-h-full w-auto  p-5 " src="logos/nett_logo.png"
             alt="logo nett"/>
        <div class="w-3/5 flex justify-center items-center">
            <h1 class="text-3xl text-white h-auto max-w-full truncate ">APLICACIÓN EJEMPLO LARAVEL</h1>
        </div>

        <div class=" w-1/5 h-auto max-w-full flex items-center space-x-4 ">
            <Link href="login" class="btn glass  text-white"> Acceder</Link>
            <Link href="register" class="btn glass  text-white"> Registrar</Link>
        </div>)}

        <div class=" w-1/5 h-auto max-w-full flex flex-row items-center space-x-4 ">
            <h2 class="text-white text-2xl ">{user.name}</h2>
            <button input class="btn glass">Logout</button>
        </div>

        <button input class="btn glass">Logout</button>
    </header>


</template>

<style scoped>

</style>
