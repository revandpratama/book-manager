<template>
    <Header>
        <Title>Book Manager</Title>
    </Header>
    <div class="p-10 flex justify-center">


        
<div class="overflow-x-auto shadow-md sm:rounded-lg">
    <div class="my-5">
        <NuxtLink to="/create" class=" bg-sky-500 text-white p-2 rounded-lg shadow hover:bg-sky-600">
            Add Book
        </NuxtLink>
    </div>
    <table class="w-full text-center text-sm text-gray-500 dark:text-gray-400">
        <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
            <tr>
                <th scope="col" class="px-6 py-3">
                    ISBN
                </th>
                <th scope="col" class="px-6 py-3">
                    Title
                </th>
                <th scope="col" class="px-6 py-3">
                    Subtitle
                </th>
                <th scope="col" class="px-6 py-3">
                    Author
                </th>
                <th scope="col" class="px-6 py-3">
                    Published
                </th>
                <th scope="col" class="px-6 py-3">
                    Publisher
                </th>
                <th scope="col" class="px-6 py-3">
                    Pages
                </th>
                <th scope="col" class="px-6 py-3">
                    Description
                </th>
                <th scope="col" class="px-6 py-3">
                    Action
                </th>
            </tr>
        </thead>
        <tbody>
            <tr class="bg-white border-b dark:bg-gray-900 dark:border-gray-700">
                <td class="px-6 py-4">
                    200120120
                </td>
                <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                    Apple MacBook Pro 17"
                </th>
                <td class="px-6 py-4">
                    This is subtitle
                </td>
                <td class="px-6 py-4">
                    Chris Aubenrt
                </td>
                <td class="px-6 py-4">
                    22 june 2023
                </td>
                <td class="px-6 py-4">
                    Meltex 
                </td>
                <td class="px-6 py-4">
                    224
                </td>
                <td class="px-6 py-4">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cumque facilis aut doloremque, iure porro saepe voluptatibus incidunt labore suscipit et?
                </td>
                <td class="px-6 py-4 flex flex-col justify-center">
                    <NuxtLink to="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Edit</NuxtLink>
                    
                    <NuxtLink to="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Delete</NuxtLink>
                    
                    <NuxtLink to="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">View</NuxtLink>
                </td>
            </tr>
            
        </tbody>
    </table>
</div>

        
    </div>
</template>

<script setup>
import { onMounted } from 'vue';
import { initFlowbite } from 'flowbite'
onMounted (() => {
    initFlowbite()
})

</script>


