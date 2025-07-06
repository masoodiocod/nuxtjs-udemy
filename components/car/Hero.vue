<template>
    <div
        class="relative  h-[95vh] w-100 bg-[url(https://carconfigurator.ferrari.com/rt-assets/data/cars/296speciale/ui/splashpage.jpg)] bg-cover bg-no-repeat bg-center">

        <div class="absolute z-10 flex justify-center items-center w-full h-full">
            <div class="text-center w-1/2">
                <h1 class="text-8xl font-serif mb-10 text-white">Find your drive</h1>
                <CarSearchBar />
                <p class="text-2xl text-white mt-10">Search for your next car by city, make, model, or price.</p>
            </div>

        </div>

        <div class="absolute z-1 bg-black h-full w-full opacity-50"></div>
    </div>
</template>