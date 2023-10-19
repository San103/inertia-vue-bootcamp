<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
import imageUrl from '@/public/images/bg.png';

// const imageUrl =  require();
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <!-- <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">Dashboard</h2>
        </template> -->

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">

                <div
                    class="overflow-hidden shadow-sm sm:rounded-lg bg-[url('/public/images/bg3.svg')] bg-cover bg-center">
                    <div class="p-6 text-gray-700 flex justify-center items-center mt-16">
                        <div class="space-y-10">
                            <div class="max-w-xl space-y-3 flex flex-col">
                                <span class="font-mono text-5xl font-bold drop-shadow-lg">Free Online Learning Resources For
                                    Dummies!</span>
                                <span class="drop-shadow-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe
                                    repellendus minus velit
                                    quam praesentium nisi eum possimus suscipit similique officiis.</span>
                            </div>
                            <form>
                                <label class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label>

                                <div class="relative ">
                                    <div class="absolute inset-y-0 left-0 flex items-center pl-7 pointer-events-none">
                                        <svg class="w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true"
                                            xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
                                            <path stroke="currentColor" strokeLinecap="round" strokeLinejoin="round"
                                                strokeWidth="2" d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z" />
                                        </svg>
                                    </div>
                                    <input type="search" id="default-search"
                                        class="block w-full p-4 pl-14 py-4 text-sm text-gray-900 border border-gray-300 rounded-full bg-gray-50 dark:bg-gray-100 dark:border-gray-300 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                        placeholder="Search here..." required />

                                </div>
                                <!-- <img src="../../../public//images/bg.png"> -->
                                <div class="space-y-8">
                                    <button type="button"
                                        class="text-white bg-blue-700 hover:bg-blue-800 focus:outline-none focus:ring-4 focus:ring-blue-300 font-medium rounded-full text-sm px-4 py-2 text-center mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                        Game Of Thrones</button>
                                    <button type="button"
                                        class="text-white bg-blue-700 hover:bg-blue-800 focus:outline-none focus:ring-4 focus:ring-blue-300 font-medium rounded-full text-sm px-4 py-2 text-center mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                                        Marvel: Avengers</button>
                                </div>

                            </form>
                        </div>


                    </div>



                </div>
               

            </div>

    </div>

</AuthenticatedLayout></template>
