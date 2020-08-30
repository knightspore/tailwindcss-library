<template>
    <div class="m-auto my-2 text-white text-left m-auto bg-red-900 rounded-md shadow-lg max-w-xs overflow-hidden">
        <img class="object-cover w-full h-48" :src=img alt="">
        <div class="pt-2 px-4 pb-6 border-t-8 border-red-800">
            <h1 class="text-2xl">{{title}}</h1>
            <span class="text-red-300 text-xs font-light">User Rating: <span class="font-bold text-red-100">{{rating}}</span> / 5</span>
            <p class="mt-2 mb-5">{{description}}</p>
            <span class="text-gray-100 text-xs font-black p-2 bg-red-700 hover:bg-red-600 hover:shadow-md rounded-md">Check Availability</span>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AccommodationCard',
    props: [
        'title',
        'description',
        'rating',
        'img'
    ]
}
</script>